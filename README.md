# CONTACT-MANAGER-APP-FULL-STACK-APPLICATION-
#!/usr/bin/avn pythons

#

Contact Manager Program

import csv

FILENAME"contacts.csv"

det write_contacts(contacts):

    With open (FILENAME. "W", newline="" ) as file:

         writer = csv.writer (file) 
         writer.writerows (contacts)

def road_contacts()

         with open(FILENANE, newline==") as file:

           reader csv.reader (file)

           for row in reader:

           contacts.append(row)
           return contacts

det list_contacts (contacts):

for i in  range(len(contacts))

contact=contacts[i] 
print(stri+1) +"."+contact[0])

print()

det view_contacts(contacts):

number = int(input("Number:"))

if number < 1 or number >len(contacts): 
print ("invalid number" )

else:

contact contacts[number-1] 
 
print("Name: contact[0])

print("Email:"+ contact[1])

print("Phone:"+contact [2])

print()

def add_contacts(contacts);

name = input("Name: ")
email=input("Email: ")
phone input("Phone:")
contact [] 
contact.append(name)
contact.append(email)
contact.append(phone) 
contacts append(contact)
write contacts(contacts)
print(name + "was added")
print()
def delete_contacts contacts):
number int(input("Number): 
if number or number Len (contacts):
print("invalid number" )
else:
contact contacts-000(number-1)
write_contacts(contacts) 
print(contact[0] was deleted")
return contacts

def display_menu():

lprint("Contact Manager") 
print()
print("COMMAND MENU" ) 
print("list Display all contacts", "Anview - View a contact" 

"\naddAdd a contact", "\ndel - Delete a contact
 inexit - Exit program)

print()

display_menu()
contacts = road_contacts()
while True:
command input=("Command: ")
list contacts(contacts).
elif comand. lower() "view": 
view_contacts(contacts) 
elif comand lower() "add":
add_contacts contacts)
elif command.lower() "del":
delete_contacts(contacts).
elif commandlower() == "exit": 
print("Good bye!"))
break
else:
   print: Invalid cenmand. Please try again.in")

if__name__=="__main__"
    main() 

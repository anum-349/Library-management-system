#Library-Management-SYATEM
##Table of Contents
#Introduction
#File Structure
#Compilation
#Running the Program
#Functionality
#Usage
#Note
#Author
##Introduction
This is a C++ program for a Library Management System, allowing users to manage information about books and students in a library. The system provides various functionalities such as displaying information, issuing and returning books, searching, updating, deleting, and adding new entries.

##File Structure
account.h: Header file containing the class definition for the account class.
account.cpp: Implementation file for the account class methods.
main.cpp: Main file containing the menu class definition and the program's entry point.
library.txt: File to store library information.
output.txt: File to store output information.

##Compilation
To compile the program, use a C++ compiler such as g++:

bash
Copy code
g++ main.cpp account.cpp -o library_management_system
Running the Program
After compilation, run the executable:

bash
Copy code
./library_management_system

##Functionality
The program provides three main menus:

Library Menu: Manage books and students in the library.
Student Menu: Manage student information.
Book Menu: Manage book information.
Each menu has various options for performing specific tasks like displaying information, issuing books, returning books, searching, updating, deleting, and adding new entries.

##Usage
Follow the on-screen instructions to navigate through the menus and perform desired actions. The system stores information in the library.txt file and creates an output.txt file for additional storage.

##Note
The program uses dynamic memory allocation for book and student objects.
Tokens are used to track the number of books issued by students.
Fine amounts are calculated for late book returns.
##Author
[ANUM KOUSAR]

**Note:** Customize placeholders like [Your Name] with actual information relevant to your program

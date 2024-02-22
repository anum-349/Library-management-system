#Introduction
#This is a simple Library Management System implemented in C++. It allows users to manage information about books and students in a library. The system provides functionalities such as displaying information, issuing and returning books, searching, updating, deleting, and adding new entries.

File Structure
account.h: Header file containing the class definition for the account class.
account.cpp: Implementation file for the account class methods.
main.cpp: Main file containing the menu class definition and the program's entry point.
library.txt: File to store library information.
output.txt: File to store output information.
Compilation
To compile the program, you can use a C++ compiler such as g++. Example:

bash
Copy code
g++ main.cpp account.cpp -o library_management_system
Running the Program
After compilation, you can run the executable:

bash
Copy code
./library_management_system
Functionality
The program provides three main menus:

Library Menu: Manage books and students in the library.
Student Menu: Manage student information.
Book Menu: Manage book information.
Each menu has various options for performing specific tasks like displaying information, issuing books, returning books, searching, updating, deleting, and adding new entries.

Usage
Follow the on-screen instructions to navigate through the menus and perform desired actions. The system stores information in the library.txt file and creates an output.txt file for additional storage.

Note
The program uses dynamic memory allocation for book and student objects.
Tokens are used to track the number of books issued by students.
Fine amounts are calculated for late book returns.
Feel free to explore and modify the code to suit your needs

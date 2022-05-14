# Library Inventory Application
## Introduction
The Library Inventory Application is a python program aimed at helping the users to keep track of the books in their inventory.
The main motivation behind the development of this application was my personal experience with my growing library. Since it is hard to remember which books you already have, for example, when shopping for books in a bookshop, I thought having such an easy-to-use app would help to avoid duplicate purchases.
Please note that, as per the assignment specifications, no external libraries were used to develop this application. 
## Development methodology
The application was developed in three phases:
### Phase 1: Design
The main goal of this phase was to determine the basic features of the application as well as the algorithms that would be incorporated into the application. For this purpose, a number of flowcharts have been designed and pseudocode was developed where needed. All design considerations were put together in a design document to be used during the implementation and testing phases.
Python 3 was selected as the language that would be used in the development of the application. 
### Phase 2: Implementation
A two-dimensional list was selected as the main data structure for the inventory due to several reasons:
•	It is possible to store values of different type to the lists.
•	It is possible to access individual elements in lists by indexes.
•	Lists are dynamic and it is possible to extend them when needed (e.g. when adding new books to the inventory).
•	Since the lists are mutable, it is possible to update the individual elements easily.
The code of the application was developed following the principles, algorithms and features described in the design document. In order to help the potential future readers and developers of the code, annotations were added to explain the purpose of the functions and avoid ambiguity. 
The structure of the application was designed as a number of functions. Menu() function was developed as the main menu of the application and when the code is run, the application starts from this function to display the main menu. Other features of the application were delivered by calling helper functions, for instance new_record() function was developed to add a new book to the inventory. Within the functions, some local functions were also developed where needed.
### Phase 3: Testing
According to the design document, three tests were carried out in order to make sure that the application works as intended:
•	Test case 1: Add five books to the inventory.
•	Test case 2: Search for a book and delete it from the inventory.
•	Test case 3: Print the inventory on the screen, sort the list by inventory number, book name and author name.
## Installation
No installation is required to use the application. You can run the project .py file from inside a python interpreter or from the command line of your system, using appropriate commands (e.g. python3 library_app.py) depending on the platform you are using.
## Features
This application has the following features:
•	Listing the books based on the inventory number, book name and author
•	Adding new books to the inventory
•	Searching for books in the inventory (by book name and author)
•	Deleting the books from the inventory
•	Querying the total number of books in the inventory
## Using the app
The application features a text-based interface. Upon running the application for the first time, a menu will be displayed. The user is supposed to enter his/her choice by pressing numeric keys and then hitting enter. In case of an invalid input, the user will be prompted again for a valid input.
Once an operation is carried out (e.g. adding a new book to the inventory), the user is redirected to the main menu.
Each book in the inventory is automatically assigned a unique inventory number. This way, uniqueness of a record is guaranteed. For instance, the user might have duplicate copies of the same book, but since each of the books are separate entities (e.g. they all add up to the total number of books), the application assigns a unique number to each of them.
In order the quit the application, the user has to go back to the main menu and make the appropriate selection.
## Potential road map for the project
The application can be further developed in two ways:
• A GUI can be introduced to make the application more user friendly. Since no external libraries were used due to the reasons explained in the Introduction section, only a text-based menu was used.
• The data of the application can be stored in a database in order to manage the data more effectively and extend the scope of data (e.g. publication house, purchase date, price, etc.)
## Queries
All queries about the application can be directed to the developer of the application, Etkin Getir, at eg22518@essex.ac.uk - All messages will be responded within 72 hours.

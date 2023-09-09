# Library-Management-Link
Library-Management-
This project is semester of Structure and Algorithms Description :

-------This is the basis app for Managing Library --------- This has 3 part : DOCGiA , DANHMUCSACH , MUONTRASACH Library Management System: We organize the following lists: Book Catalog: a linear list represented as an array of pointers (ISBN, Title, Number of Pages, Author, Publication Year, Genre, pointer): the pointer will point to the corresponding books in the catalog.

Book List: a singly linked list (Book Template, Status, Location). Each book has a unique code; the book status includes: 0: available for borrowing, 1: borrowed by a reader, 2: book has been disposed of.

Reader List: a binary search tree (Reader ID (randomly generated integer), First Name, Last Name, Gender, Card Status, pointer): the pointer will point to the list of books that the reader has borrowed.

Borrow List: a singly linked list (Book Code, Borrow Date, Return Date, Status): status = 0 means the book is currently borrowed (not returned), status = 1 means it has been returned, status = 2: book is lost. The program has the following functionalities:

a. Reader Management: add/delete/modify reader information. The reader ID is automatically generated randomly and does not duplicate existing reader IDs; Gender can only be 'Male' or 'Female'; card status = 0 when the card is locked, card status = 1 when the card is active (allow borrowing books).

b. Print Reader List: display the list of readers in ascending order of first name + last name or in ascending order of reader ID according to the librarian's preference.

c. Enter book catalog and automatically assign book codes. d. Print the list of books in the library in alphabetical order of book titles.

e. Search book information by book title: display ISBN, book title, author, publication year, genre, and the available book codes in the library.

f. Borrow books: enter the reader ID, and the program will list the books that the reader is currently borrowing. Each reader can borrow a maximum of 3 books and cannot borrow if holding a book past the due date (15 days).

g. Return books.

Author :

Nguyen Quang Binh
Pham Huy Hoang
Chau Thanh Dat
Nguyen Thanh Dien
Download it !!

git clone https://github.com/sprchuoi111/Library-Management-.git
unzip and run file .exe Contact : https://www.facebook.com/sprchuoi/

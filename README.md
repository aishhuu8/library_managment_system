# library_managment_systemMySQL_project
Library Management System Database
This project involves the creation of a database for a Library Management System. It aims to efficiently manage information about books, employees, customers, and their interactions within the library.
Tables in the Database:
1)Branch: Stores information about library branches including branch number, manager ID, address, and contact number.
2)Employee: Contains details of library employees such as employee ID, name, position, salary, and the branch they belong to.
3)Books: Holds data regarding books available in the library including ISBN, title, category, rental price, availability status, author, and publisher.
4)Customer: Stores customer information like customer ID, name, address, and registration date.
5)IssueStatus: Records issued books by customers including issue ID, customer ID, book name, issue date, and ISBN.
6)ReturnStatus: Tracks returned books including return ID, customer ID, book name, return date, and ISBN.
Queries:
The database supports various queries for efficient management of library resources and operations, including:
1)Retrieving available book titles, categories, and rental prices.
2)Listing employee names and salaries in descending order of salary.
3)Displaying book titles and the corresponding customers who have issued those books.
4)Calculating the total count of books in each category.
5)Retrieving employee names and positions for those with salaries above Rs.50,000.
6)Listing customer names who registered before 2022-01-01 and haven't issued any books yet.
7)Displaying branch numbers and the total count of employees in each branch.
8)Listing names of customers who issued books in June 2023.
9)Retrieving book titles containing "history" from the book table.
10)Retrieving branch numbers along with the count of employees for branches having more than 5 employees.

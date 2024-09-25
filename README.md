Library Management System - SQL Project

Overview: This project involves creating a database to manage various aspects of a library, including books, authors, members, and loans. The system allows for efficient tracking of which members have borrowed which books, along with managing details about authors and the books available in the library.

Key Components:

Database Setup: The project begins by creating a dedicated database named Library_Management_system where all library-related data is stored and managed.

Authors Table: The system stores information about the authors of the books in the library. Each author has a unique ID, a name, and a birthdate. Constraints ensure that all data entered is valid, such as making sure no author has a future birthdate.

Books Table: This table stores all the essential information about each book, including the book's title, genre, year of publication, and ISBN number (which is unique for each book). Each book is also linked to an author through a foreign key relationship with the Authors table.

Members Table: Library members are tracked with details such as their name, email, and the date they joined the library. This ensures that each member can be uniquely identified, and their membership status is kept up to date.

Loans Table: The system also tracks book loans, linking specific books to members who have borrowed them. The loans table stores details like the loan date and references both the book and the member involved in the transaction.

Data Insertion and Queries:

The system includes inserting sample data into the tables, such as author names, book titles, and member details.
Queries are used to retrieve information like which books are borrowed by specific members, the authors of the books, and the details of members who haven't borrowed any books yet.
It supports both simple queries, like selecting all authors or books, and more complex joins that show data from multiple tables.
Views and Procedures:

The system creates a view called BorrowedBooks, which provides an easy way to see the details of books currently on loan, along with the members who borrowed them and the loan dates.
Stored procedures are included to simplify the process of inserting or updating book details, allowing library administrators to manage books with minimal effort.

This SQL-based Library Management System is designed to streamline the management of a library, offering both efficient data storage and flexible queries for retrieving essential information.

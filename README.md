# library-management_sql

## Project Overview

The Library Management System is designed to automate and manage the library's core operations, such as issuing books, tracking book availability, and managing user accounts. This system categorically organizes the books, tracks their prices, statuses, and the total number available, making it easier for both the library staff and users to manage and access the library's resources.

## Features

- **Book Management**: Manage books with details like title, publisher, and branch availability.
- **Borrower Management**: Track borrowers with unique card numbers, ensuring seamless book issuance and returns.
- **Book Loans**: Issue books to borrowers, track due dates, and manage loan records.
- **Library Branches**: Manage multiple library branches with their specific inventories.

## Database Structure

The system is built on a SQL-based relational database with the following key tables:

1. **`tbl_publisher`**: Stores publisher details.
2. **`tbl_book`**: Stores book details and their associated publishers.
3. **`tbl_library_branch`**: Manages details of library branches.
4. **`tbl_borrower`**: Keeps track of borrower information.
5. **`tbl_book_loans`**: Tracks book loan details.
6. **`tbl_book_copies`**: Manages the number of copies of books available in different branches.

## Setup Instructions

1. **Database Setup**:
   - Use the provided SQL file (`library_management_sql.sql`) to create the database and the necessary tables.
   - Execute the script on your SQL Server instance to set up the library management system.

2. **Execution**:
   - After setting up the database, the system is ready to use for managing library operations.

3. **Queries**:
   - Sample queries are provided within the SQL file to help retrieve data from the database, such as selecting all borrowers or books in a specific branch.

## Future Enhancements

- **User Authentication**: Add login functionality for library staff and users.
- **Book Reservation**: Allow users to reserve books online.
- **Overdue Fines**: Implement a system to automatically calculate and manage fines for overdue books.

## Contributing

Feel free to contribute by submitting a pull request. Please ensure your changes are well documented and tested.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

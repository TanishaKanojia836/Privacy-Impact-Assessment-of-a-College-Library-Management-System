# 03 - Data Flow

## Data Flow

1. Student logs into the library application.
2. The application authenticates the student.
3. Student searches for or borrows a book.
4. The application sends the transaction to the library server.
5. The server stores the relevant information in the database.
6. Authorized librarians can access information required for library operations.
7. Students can access their own account and borrowing information.

## Basic Data Flow

Student
↓
Library Application
↓
Library Server
↓
Database
↓
Authorized Librarian / Administration

## Privacy Considerations

At every stage, access to personal information should be restricted to authorized users.

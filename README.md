Library Management System - README

Description:
This is a simple command-line Library Management System implemented in Python. 
It allows librarians to manage book records, including adding new books, 
displaying all books, searching for books, borrowing and returning books, 
and saving/loading records to/from a file.

Features:
- Add new books with title, author, year published, and ISBN
- Display all books in the library with their availability status
- Search for books by title or author
- Borrow books (marks them as unavailable)
- Return books (marks them as available again)
- Automatic loading of records when program starts
- Automatic saving of records when program exits

Requirements:
- Python 3.x

How to Run:
1. Save the code to a file named 'library_management.py'
2. Open a terminal/command prompt
3. Navigate to the directory containing the file
4. Run the command: python library_management.py

Usage:
- Follow the on-screen menu prompts
- Enter the corresponding number for each action
- For adding books, provide all requested details
- For borrowing/returning, you'll need the book's ISBN
- The system will automatically save records when you exit

File Storage:
- Book records are stored in 'library_records.txt' in JSON format
- This file is created automatically in the same directory as the script
- Existing records are loaded automatically when the program starts

Note:
The system is designed to be simple and doesn't include user authentication 
or advanced features like due dates for borrowed books.

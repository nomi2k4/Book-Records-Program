Book Records Program

A simple C++ program to store and retrieve book records.

Overview
This program allows users to input details of up to 16 books, including book ID, title, author, and price. It then displays the titles of books with a price greater than 600.

Features
- Stores book records in a structured array
- Allows user input for book details
- Displays titles of books with a price greater than 600

Requirements
- C++ compiler (e.g., GCC)
- Standard C++ libraries (e.g., iostream, string)

Usage
1. Compile the program using a C++ compiler (e.g., g++ book_records.cpp -o book_records)
2. Run the program (e.g., ./book_records)
3. Follow the prompts to input book details
4. The program will display the titles of books with a price greater than 600

Notes
- This program uses a fixed-size array to store book records. For larger datasets, consider using dynamic memory allocation or a container class like std::vector.
- Error handling is minimal in this program. Consider adding checks for invalid user input or other potential errors.
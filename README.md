# Library Management Application

A JavaScript-based miniature library application that allows users to manage a collection of books, track borrowing status, search and filter books.

## Features

- **Book Management**
  - Add new books with title, author, genre, year, and description
  - Delete books from the collection
  - Track availability status (available/borrowed)

- **Borrowing System**
  - Borrow books with borrower information
  - Return borrowed books
  - Status indicators for each book

- **Search and Filtering**
  - Search books by title or author
  - Filter by genre or status
  - Pagination for large collections

- **Data Persistence**
  - Stores library data in localStorage
  - Loads data on application startup
  - Sample books added automatically on first run

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- LocalStorage API

## Installation & Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/library-application.git
   ```

2. Navigate to the project directory:
   ```
   cd library-application
   ```

3. Open the application:
   - If using VS Code with Live Server:
     ```
     code .
     ```
     Then right-click on `index.html` and select "Open with Live Server"
   
   - Or simply open the `index.html` file in any web browser

## Usage

### Adding a Book
1. Click the "Add New Book" button
2. Fill in the book details in the form
3. Click "Save Book"

### Borrowing a Book
1. Find the book in the library table
2. Click the "Borrow" button
3. Enter the borrower's name when prompted

### Returning a Book
1. Find the borrowed book in the library table
2. Click the "Return" button

### Searching and Filtering
- Use the search box to find books by title or author
- Use the dropdown filters to filter by genre or availability status

## Project Structure

```
library-application/
├── index.html     # Main HTML file with embedded CSS and JavaScript
├── README.md      # Project documentation
└── LICENSE        # License information
```

## Future Enhancements

- User authentication system
- Backend server integration
- Book cover image upload
- Due date notifications
- Advanced reporting features

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Your Name - [your-github-username](https://github.com/yourusername)

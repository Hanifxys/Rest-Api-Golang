## Go CRUD REST API Example

This is a simple CRUD (Create, Read, Update, Delete) RESTful API example implemented in Go. It allows you to manage a collection of books.

### Installation and Run

Follow these steps to install and run the project:

1. **Download the Project:**
   - Download or clone this project from the repository.

2. **Navigate to the Project Directory:**
   - Open a terminal or command prompt.
   - Change directory to the root of the project.

3. **Build the Project:**
   - Run the following command to build the project:
     ```
     go build
     ```

4. **Run the Application:**
   - Execute the built binary to run the application:
     ```
     ./restapi
     ```

5. **Access the API:**
   - Open a web browser or use an API testing tool like Postman.
   - Go to the following URL to access the API:
     ```
     http://localhost:8000/api/books
     ```

### API Endpoints

- **GET /api/books**: Get a list of all books.
- **GET /api/books/{id}**: Get details of a specific book by ID.
- **POST /api/books**: Create a new book.
- **PUT /api/books/{id}**: Update an existing book by ID.
- **DELETE /api/books/{id}**: Delete a book by ID.

### Data Format

The API accepts and returns data in JSON format. Here's the structure of a book object:

```json
{
  "id": "1",
  "isbn": "445566",
  "title": "Book One",
  "author": {
    "firstname": "Muhamad",
    "lastname": "Hanif"
  }
}
```

### Dependencies

This project uses the following dependencies:
- **github.com/gorilla/mux**: A powerful HTTP router and URL matcher for building Go web servers.

### Future Improvements

Possible future enhancements for this project include:
- Adding database integration for persistent storage.
- Implementing authentication and authorization mechanisms.
- Enhancing error handling and validation.
- Implementing pagination for large datasets.

Feel free to contribute to this project and make it even better!
# Book Catalog Web Application

This is a simple web application built with Node.js and Express that allows users to manage a catalog of books. It uses a MongoDB database to store and retrieve book information. You can use this README to understand the API endpoints and their usage, set up the application locally, and learn about key decisions and assumptions made during the development process.

## API Endpoints and Usage

### 1. **GET /**

- This route is not fully defined in the code but seems to be intended to display a web page.
- It might be used to welcome users or provide information about the application.

### 2. **GET /show**

- Displays a list of books from the MongoDB collection.
- Usage: Access the book list by visiting `/show` in your web browser.

### 3. **POST /show**

- Handles the creation of new book entries.
- Usage: Submit a form with book details to add a new book to the catalog.

### 4. **GET /edit/:id**

- Allows users to edit a specific book entry.
- Usage: Visit `/edit/:id` where `:id` is the ObjectId of the book you want to edit. This route will render an edit form.

### 5. **POST /edit/:id**

- Handles the submission of edited book information.
- Usage: Submit the edited book details using the edit form, and it will update the book in the catalog.

### 6. **GET /delete/:id**

- Used to delete a specific book entry.
- Usage: Visit `/delete/:id` where `:id` is the ObjectId of the book you want to delete. The book will be removed from the catalog.

## Set Up and Run Locally

To run this application locally, follow these steps:

1. **Clone the Repository**:

2. ** Then in terminal, write npm i **

3. ** Add your mongo Db url/uri **

4. ** then in terminal write nodemon/node index.js **

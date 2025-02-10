# Library Management System

## Overview

The **Library Management System** is a Java-based desktop application with a graphical user interface (GUI) designed to manage library operations efficiently. It allows librarians to manage books, users, and transactions seamlessly.

## Features

- **User Management**:
  - **Add Users**: Register new users into the system.
  - **Update User Information**: Modify existing user details.
  - **Delete Users**: Remove users from the system.

- **Book Management**:
  - **Add Books**: Catalog new books into the library.
  - **Update Book Details**: Edit information of existing books.
  - **Delete Books**: Remove books from the catalog.
  - **Search Books**: Find books by title, author, or ISBN.

- **Transaction Management**:
  - **Issue Books**: Lend books to registered users.
  - **Return Books**: Process the return of borrowed books.
  - **View Transaction History**: Track all lending and returning activities.

## Technologies Used

- **Programming Language**: Java
- **GUI Framework**: Swing
- **Database**: MySQL
- **IDE**: IntelliJ IDEA

## Installation and Setup

To run the Library Management System locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/omkar04gaikwad/LibraryManagmentSystem.git
   cd LibraryManagmentSystem/LibrayManagementSystem
   ```

2. **Database Configuration**:
   - [Provide instructions to set up the database, e.g., "Install MySQL and create a database named `library_db`."]
   - [Provide instructions to import any necessary tables or data, e.g., "Run the `schema.sql` script located in the `resources` folder to set up the tables."]

3. **Configure Database Connection**:
   - Open the project in your preferred IDE.
   - Locate the database configuration file or the section in the code where the database connection is established.
   - Update the connection parameters (URL, username, password) to match your local database setup.

4. **Build and Run the Application**:
   - Compile the project using your IDE's build tools.
   - Run the `Main` class to launch the application.

*Note*: Ensure you have the Java Development Kit (JDK) installed on your system.

## Usage

1. **Launch the Application**:
   - Execute the compiled application to open the GUI.

2. **Navigate Through the GUI**:
   - Use the menu options to manage users, books, and transactions.
   - Fill out the forms provided in each section to perform the desired operations.

3. **Save and Retrieve Data**:
   - All data entered through the GUI is stored in the connected database.
   - Use the search functionalities to retrieve and view existing records.


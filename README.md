# go-bookstore

# Bookstore Management REST API

This project is a feature-rich REST API built using Go, MySQL, and ORM. It serves as a versatile CRUD system, empowering users to effectively manage and search for information related to various books within a store based on their unique identifier.

## Features

- **Go:** The API is developed using Go, a powerful and efficient programming language known for its simplicity and concurrency features.

- **MySQL:** MySQL is used as the data storage solution for managing book information. You can create a MySQL database and define a schema with tables such as "Books" to store details like book title, author, genre, ISBN, etc.

- **ORM (Object-Relational Mapping):** The API utilizes an ORM library like GORM or XORM for Go, which simplifies database operations by providing an abstraction layer. This allows you to define Go struct models that map to database tables and perform CRUD operations on the database using Go code.

- **CRUD System:** The API functions as a versatile CRUD system, enabling users to perform Create, Read, Update, and Delete operations on book records in the database. Users can send HTTP requests to create new book entries, retrieve book details based on unique identifiers (e.g., book ID), update book information, and delete books from the database.

- **Testing with Postman:** Postman is used for testing and development. You can create Postman collections that define different API endpoints, request payloads, expected responses, and tests. This ensures the API functions correctly and provides an easy way to validate its behavior.

- **Documentation:** Documentation is automatically generated using Postman. It includes details about how to use the API, the expected structure of requests and responses, and any additional information developers may need to interact with the API effectively.

## Getting Started

To get started with the API, follow these steps:

1. Clone the repository: `git clone https://github.com/Tripti-09/bookstore-api.git`
2. Install the necessary dependencies: `go mod download`
3. Set up your MySQL database and configure the connection details in the API's configuration file.
4. Run the API: `go run main.go`
5. Use Postman to test the API endpoints and access the automatically generated documentation.

## Contributing

Contributions to the project are welcome! If you find any issues or want to add new features, feel free to submit a pull request. Please ensure to follow the guidelines outlined in the CONTRIBUTING.md file.

## License

This project is licensed under the [MIT License](LICENSE).

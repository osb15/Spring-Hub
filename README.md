# JDBC with Maven

This repository provides a basic implementation of JDBC (Java Database Connectivity) using Maven for dependency management. The project demonstrates how to connect a Java application to a database, execute queries, and handle results efficiently.

---

## Features

- Simple and lightweight JDBC setup.
- Utilizes Maven for dependency management.
- Demonstrates database connection, querying, and result handling.
- Easy to extend and integrate into other projects.

---

## Prerequisites

- Java Development Kit (JDK) installed (version 8 or higher).
- Apache Maven installed.
- A running database instance (e.g., MySQL, PostgreSQL).
- Basic knowledge of SQL and Java programming.

---

## Getting Started

1. Clone this repository:

   ```bash
   git clone <repository-link>
   ```

2. Navigate to the project directory:

   ```bash
   cd jdbc-with-maven
   ```

3. Update the `application.properties` file with your database credentials:

   ```properties
   db.url=jdbc:mysql://localhost:3306/your_database
   db.username=root.
   db.password=root.
   ```

4. Build the project using Maven:

   ```bash
   mvn clean install
   ```

5. Run the application:

   ```bash
   java -jar target/jdbc-with-maven-1.0.jar
   ```

---

## Dependencies

The project uses the following dependencies:

- JDBC Driver (e.g., MySQL Connector): Handles communication with the database.
- Apache Maven: Manages the project's build and dependencies.

For a full list of dependencies, refer to the `pom.xml` file in the project.

---

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Repository Link

[View the Repository on GitHub](https://github.com/osb15)

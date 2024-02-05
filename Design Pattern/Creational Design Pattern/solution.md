
# ShopWorldapp Project

This project is a simple application that demonstrates the use of Singleton, Factory, and Builder design patterns in Java.

## Getting Started

To get started with the ShopWorldapp project, follow these steps:

1. Clone the repository to your local machine.
2. Open the project in your preferred Java IDE.
3. Run the `ShopWorldapp` class to execute the application.

## Project Structure

The project follows the standard Java project structure. Here's a brief overview:

- `entities/` - Contains the entity classes that define the objects used in the application.
  - `Product.java` - Defines the Product object.
  - `UserAccount.java` - Defines the UserAccount object.
  - `Order.java` - Defines the Order object.
- `dal/` - Contains the data access layer classes that interact with the database.
  - `userdb.java` - Provides methods to interact with the user database.
- `ShopWorldapp.java` - The main entry point of the application.

## Design Patterns

The following design patterns are used in this project:

- **Singleton:** The `userdb` class is implemented as a Singleton to ensure that only one instance of the class is created throughout the application.
- **Factory:** The `ProductFactory` class is implemented as a Factory to create instances of the Product object based on the input string.
- **Builder:** The `UserAccount` and `Order` classes are implemented using the Builder pattern to create complex objects step by step.

## Building the Project

To build the project, use the following command:

```bash
mvn clean install

Testing the Project

To test the project, use the following command:

bash
Copy code
mvn test

Contributing

We welcome contributions from the community. Before submitting a pull request, please read our contributing guidelines.




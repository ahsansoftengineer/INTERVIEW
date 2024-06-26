### REPOSITORY PATTERN
What is the use case of repository design pattern?
The Repository Pattern is a design pattern that provides an abstraction layer between the data access layer and the rest of the application. It separates the logic that retrieves data from the data storage layer, providing a more modular approach to software development.

The repository pattern is a design pattern commonly used in software development to abstract the data access layer.

Abstracting the data access layer means creating a separation or interface between your application's business logic and the specific mechanisms used to retrieve and manipulate data from a data source, such as a database. This separation provides several benefits, including:
1. **Flexibility**: for Changing / Swapping Database
2. **Testability**: you can use Mocks
3. **Maintainability**: when change of code occur doesn't need to updated whole application
4. **Security**: can manage security at one place only

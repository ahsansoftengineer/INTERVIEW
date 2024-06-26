## SOLID 


### SOLID (Single Responsi.. , Open Closed, Liskov Substitution, Dependency Inversion)
SOLID is an acronym that represents a set of five design principles in object-oriented programming, intended to help developers create more maintainable and flexible software. Here's a brief explanation of each SOLID principle:

1. **Single Responsibility Principle (SRP)**:
- A class should have only one reason to change, meaning it should have a single responsibility.
- Each class or module should focus on doing one thing well, making the code easier to understand, modify, and maintain.

2. **Open/Closed Principle (OCP)**:
- Software entities (classes, modules, functions) should be open for extension but closed for modification.
- You can add new functionality to existing code without changing its source code, promoting code reuse and reducing the risk of introducing bugs.

3. **Liskov Substitution Principle (LSP)**:
- Subtypes must be substitutable for their base types without altering the correctness of the program.
- It ensures that derived classes can be used interchangeably with their base classes, maintaining the expected behavior.
- If a class S is a subclass of class T, an object of class T should be replaceable with an object of class S without affecting the functionality of the program.

4. **Interface Segregation Principle (ISP)**:
- Clients should not be forced to depend on interfaces they don't use.
- Divide large interfaces into smaller, more specific ones to avoid forcing clients to implement methods they don't need.

5. **Dependency Inversion Principle (DIP)**:
- High-level modules should not depend on low-level modules. Both should depend on abstractions.
- Abstractions (interfaces or abstract classes) should be used to decouple high-level and low-level components, making the system more flexible and allowing easier substitution of components.

SOLID principles help create code that is more modular, easier to maintain, and less prone to bugs. Following these principles can lead to well-structured, flexible, and extensible software designs.

## SOLID TABLE
| Heading | Defination |
|:-------:|:---------- | 
| Single Responsibility (SRP)  | Class, Function has the Only 1 Reason to Change |
| Open-Closed Principle (OCP)  | Make your function as flexible that it can used over and over again |
| Liskov Substitution (LSP)    | To apply the Liskov substitution principle in your code, you should make sure that any subclasses you create adhere to the same interface and behavior as their parent class. You should also avoid making any changes to the behavior of the parent class that would affect the behavior of the subclass. By doing so, you can ensure that your code is robust, reliable, and easy to maintain over time. |
| Interface Segregation (ISP)  | Don't Make Huge Interface, Split the Big Interface into multiple small Interfaces |
| Dependency Inversion (DIP)   | Dependency Inversion (DI) is a principle that states that high-level modules should not depend on low-level modules, but both should depend on abstractions. This means that instead of directly depending on concrete implementations of classes or modules, we should depend on interfaces or abstract classes that define the behavior we need. |
| Dependency Injection | Dependency Injection (DI) is a technique used to implement Dependency Inversion. It involves passing dependencies into a class or module from an external source, rather than having the class or module create them internally. This allows us to change the behavior of a class or module by changing the dependencies passed to it, without having to modify its code. |
| Keep it Simple Stupid (KISS) | KISS is an acronym that stands for "Keep It Simple, Stupid." It is a principle of software design that suggests that the simplest solution is often the best one. The KISS principle encourages developers to avoid overcomplicating things and to favor simple, straightforward designs over complex ones.  |
| IOC Container | In software development, an IOC (Inversion of Control) container is a framework or tool that automates the process of dependency injection. An IOC container manages the dependencies of various objects or components in an application, and provides them with the required dependencies when they are needed.|

### Liskov vs Open Closed Principal
- The Liskov substitution principle is a concept in object-oriented programming that was introduced by Barbara Liskov in 1987. It states that if a program is designed to work with objects of a certain class, it should be able to work with objects of any subclass of that class without any problems.
- The Liskov substitution principle is focused on ensuring that a program is designed in a way that allows objects of a subclass to be used in place of objects of the parent class without any issues. It is designed to ensure that a program is flexible and maintainable, by allowing new classes to be added to the program without affecting the existing code.
- The Liskov substitution principle is based on the assumption that subclasses inherit all the characteristics and behavior of the parent class, and that any changes made to the subclass should not affect the functionality of the program. This allows you to use objects of any subclass of a class interchangeably with objects of the parent class, without any issues or unexpected behavior.
- The Open/Closed principle, on the other hand, is focused on ensuring that a program is designed in a way that allows it to be easily extended without modifying the existing code. It is designed to ensure that a program is robust and reliable, by allowing new functionality to be added to the program without introducing new bugs or issues.

### Programing Paradiagm 
| Heading | Defination |
|:-------:|:---------- | 
| Procedural Programing | Procedural programming is a programming paradigm that focuses on describing a series of procedures or functions that manipulate data. Procedural programming languages are typically used to write large, complex programs, where data is organized into variables, arrays, and structures, and operations are performed through a series of functions or subroutines. | 
| Object Oriented Programing | OOP languages provide support for encapsulation, inheritance, and polymorphism, which are key concepts that help to make OOP programs more flexible, reusable, and maintainable. |
| Functional Programing | Functional programming (FP) is a programming paradigm that focuses on the use of functions to solve problems, rather than using mutable data structures and objects. In FP, functions are treated as first-class citizens, which means that they can be passed around as arguments to other functions, and can be returned as values from functions. |




| Async Programming in DotNet | |


### Programming Terms
| Heading | Defination |
|:-------:|:---------- | 
| POCO, POJO | 1. POCO stands for Plain Old CLR (Common Language Runtime) Object and is a concept in the .NET framework. POCO is a class that does not have any dependencies on external libraries or frameworks and does not implement any interfaces or inherit from any base classes, making it easy to use and test. 2. POJO stands for Plain Old Java Object and is a concept in the Java programming language. POJO is a class that is not bound by any framework-specific requirements and does not inherit from any framework-specific classes. POJOs are simple, self-contained objects that can be easily used and tested. |
| Database Migrations | Database migrations typically involve creating a script or set of scripts that define the changes to be made to the database schema, and then running those scripts against the database to apply the changes. Database migrations can be either forward migrations, which add new functionality to the database, or backward migrations, which remove or modify existing functionality. |
| Database Seeding | In the context of database management systems, seeding refers to adding data to a database table using scripts or programs. The data is usually pre-defined and can be used for a variety of purposes such as to populate a database with default values or test data, to add lookup values, or to provide reference data that is used throughout the application. | 
| Scaling | Virtual scaling and horizontal scaling are two different approaches to increasing the capacity of a system. |
| Virtual scaling | Involves increasing the capacity of a single machine or server by adding more resources, such as CPU, RAM, or storage. For example, you might upgrade a server by adding more RAM or installing a faster CPU. Virtual scaling can be relatively easy to implement, but it can also be expensive and have limitations in terms of scalability. |
| Horizontal Scaling |  adding more machines or servers to the system to increase capacity. In this approach, the workload is distributed across multiple machines, with each machine handling a smaller portion of the overall workload. Horizontal scaling can be more cost-effective than vertical scaling and can provide better scalability, but it can also be more complex to implement and manage. |

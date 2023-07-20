# Dependency Injection & Repository Design Pattern

## why this topic matters as it relates to what Iam studying in this module?

- **Dependency injection**: makes it easier to change the behavior of an application by changing the components that implements the interfaces that define application features. It also results in components that are easier to isolate for unit testing.

- **SOLID Principles**: they lead to more maintainable, flexible, and extensible code. They promote testability and enhance code quality by encouraging clean and well-structured code, making it easier to read and maintain. Adhering to these principles fosters collaboration among developers as the codebase follows consistent and understandable patterns and structure, ultimately resulting in more efficient and reliable software development.

- **Repository pattern**: it abstracts away the complexities of data access and provides a clean and consistent interface for working with data, so this lets you focus on the data persistence logic rather than on data access plumbing. And it makes the code more organized, easier to maintain, and allows you to switch databases or data storage technologies with minimal impact on the rest of your application.

## Dependency injection

**Dependency injection**:

Dependency Injection makes it easy to create loosely coupled components, which typically means that components consume functionality defined by interfaces without having any first-hand knowledge of which implementation classes are being used.

**How is it used**:

The Startup class is used to specify which implementation classes are used to deliver the functionality specified by the interfaces used by the application. When new objects such as controllers-are created to handle requests, they are automatically provided with instances of the implementation classes they require.

**Advantegse**:

- Helps with adhering to the Dependency Injection Principle ( DIP).
- Allows objects to be easily swapped with replacements Facilitates the use of the strategy design pattern (SDP).
- Improves testability.
- Enables loose soupling of software components.

**Disadvantegse**:

- Dl introduces a learning curve.
- DI requires significant overhaul of some existing projects.
- Some timelines may not allow for D.I.

## SOLID Principles

- Single responsibility principle: Each class should only be responsible for one primary function. This encourages better class naming and discourages developers from making a class more than it needs to.

- Open-Closed Principle: Objects should be open for extension, while remaining closed for modifications. This encourages creation of subclasses for added functionality without breaking existing code.

- Liskov Substitution Principle: objects should be replicable with appropriate objects. For example, other objects that share the same parent class or common interface. This enables loose coupling of related objects.

- Interface Segregation Principle instead of overusing one generic interface, It is better to have more interfaces, well suited for specific purposes. His encourages you to keep each interface lightweight.

- Dependency Inversion Principle: Objects should be decoupled or loosely coupled. This forces classes to depend on the abstract definition of another object instead of a concrete implementation.

## Repository pattern

is a design pattern used to manage data access and interaction with the underlying database. It provides a structured way to handle data operations, like retrieving, storing, updating, and deleting data, in your web application. Instead of writing database code directly in your controllers or services, you create a separate "Repository" class that acts as an intermediary between your application code and the database. The Repository class provides methods that allow you to interact with the data in a more organized and consistent manner.

## Things I want to know more about

nothing for now.

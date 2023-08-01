# Testing and Swagger and Deployment

### Swagger

Swagger (OpenAPI) is a language-agnostic specification for describing REST APIs. It allows both computers and humans to understand the capabilities of a REST API without direct access to the source code. Its main goals are to:

- Minimize the amount of work needed to connect decoupled services.
- Reduce the amount of time needed to accurately document a service.

### Swagger UI

Swagger UI offers a web-based UI that provides information about the service, using the generated OpenAPI specification. Each public action method in your controllers can be tested from the UI.

### Unit testing controller logic in ASP.NET Core

Unit testing controller logic involves testing the behavior and functionality of the controller methods in isolation from the rest of the application. This is achieved by mocking dependencies and providing controlled inputs to the controller methods.

### Why this topic matters as it relates to what you are studying in this module

- **Swagger UI** plays a vital role in API development, testing, and consumption by providing a user-friendly interface for understanding, interacting with, and documenting RESTful APIs. It enhances productivity, reduces errors, and fosters better collaboration among developers and API consumers.

- **Unit testing** for ASP.NET MVC applications in C# is an essential practice that helps improve code quality, maintainability, and collaboration while providing faster feedback and reducing the likelihood of introducing defects during development.

- **testing controller**: When unit testing controller logic, only the contents of a single action are tested, not the behavior of its dependencies or of the framework itself.Set up unit tests of controller actions to focus on the controller's behavior. A controller unit test avoids scenarios such as filters, routing, and model binding. Tests that cover the interactions among components that collectively respond to a request are handled by integration tests.

## Things I want to know more about

The implementation of DTOs in our lab to practice it.

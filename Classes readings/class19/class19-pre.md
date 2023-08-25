# Roles, Claims and JWT Tokens

## why this topic matters as it relates to what Iam studying in this module?

Roles help categorize users based on their roles and responsibilities, claims provide specific information about a user, and JWT tokens are a secure way to package and transmit this information for authentication and authorization purposes in ASP.NET Core MVC applications.

## Roles

Roles are used to group users based on their responsibilities or permissions within an application. For example, an application might have roles like "Admin," "User," and "Guest." Users with different roles can access different parts of the application and perform different actions. Roles help in managing access control and ensuring that users only have access to the features they're authorized to use.

## Claims-based authorization in ASP.NET Core

- Claims are pieces of information about a user that describe their identity or attributes. Claims can be things like a user's name, email, role, age, etc. They provide context and details about the user's characteristics. Claims are often used in authentication and authorization processes to determine what a user is allowed to do within an application based on their attributes.

- When an identity is created it may be assigned one or more claims issued by a trusted party. A claim is a name value pair that represents what the subject is, not what the subject can do.

### Adding claims checks

Claim based authorization checks:

- Are declarative.
- Are applied to Razor Pages, controllers, or actions within a controller.
- Can not be applied at the Razor Page handler level, they must be applied to the Page.

## The difference between Authentication and Authorisation

First of all, we should clarify the difference between these two dependent facets of security. The simple answer is that Authentication is the process of determining who you are, while Authorisation revolves around what you are allowed to do, i.e. permissions. Obviously before you can determine what a user is allowed to do, you need to know who they are, so when authorisation is required, you must also first authenticate the user in some way.

## JWT Authentication

- JSON Web Token (JWT) is a means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS) and/or encrypted using JSON Web Encryption (JWE).

- JWT tokens are a type of compact and self-contained data format that is used for securely transmitting information between parties. In the context of ASP.NET Core MVC, JWT tokens are commonly used for authentication and authorization. These tokens are digitally signed and can carry claims about the user, like their ID, roles, or other attributes. When a user logs in, they receive a JWT token that they can include in their subsequent requests. The server then verifies the token's integrity and extracts claims to determine the user's identity and permissions.

## Things I want to know more about

How to benefits from all identity features and combine them togather in real apps to result to a strong user identity.

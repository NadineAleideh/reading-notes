# Identity

## why this topic matters as it relates to what Iam studying in this module?

ASP.NET Core Identity is a crucial component for web applications, ensuring user data security, streamlined user management, and controlled access. It simplifies authentication, password management, and role-based authorization, saving time and reducing errors. Its customization options allow tailoring to specific needs, while integration with other ASP.NET Core parts ensures seamless functionality. By handling standard user tasks, Identity enhances scalability, compliance adherence, and user experience, making it a vital tool for developers.

## Intro to Identity

ASP.NET Core Identity is an API that provides user interface login functionality; and manages various user-related tasks such as user registration, password management, roles, and token-based authentication.

It provides a way to create and handle user identities with claims, which represent specific facts about users.

Users can either create an account with login information stored in Identity or use external login providers like Google, Microsoft Account, etc.

Identity is commonly configured with a SQL Server database to store user data, but other persistent stores like Azure Table Storage can be used as well.

The tutorial includes steps for Creating an ASP.NET Core Web Application project with Individual User Accounts:

- Create new ASP.NET Core Web App project and name the project as desired.
- In the Authentication type input, select Individual User Accounts.
- Click OK to create the project with authentication enabled.
- Visual Studio will set up the project with authentication using Identity framework and related components.
- Build and run the project to see the basic authentication setup in action, which can be extended to fit our requirements.

## Identity Demystified

ASP.NET Core 2.0 Authentication and Authorization System Demystified

The system uses verbs like Authenticate, Challenge, SignIn, SignOut, and Forbid to execute authentication and authorization tasks.

Authentication handlers are responsible for implementing these behaviors, and they are registered with the authentication middleware. This middleware runs on every request, allowing the system to check user authentication and authorization and handle requests accordingly.

By using these components together, you can effectively authenticate and authorize users to access resources on your website.

## Things I want to know more about

nothing for now.

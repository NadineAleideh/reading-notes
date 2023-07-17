# Entity Framework and APIs

## why this topic matters as it relates to what Iam studying in this module?

.NET developers benefit from Entity Framework because it eliminates a lot of the data-access code that they normally have to write. using Entity Framework increases our productivity as a developer's, in this way, we have the ability to manipulate data using objects of domain-specific classes without having to deal with the underlying database tables and columns. Regarding APIs, they are also vital to .NET developers because they can streamline resource and data sharing, control access through authentication and rights definition, and ensure safety.

## Entity Framework Core

Entity Framework Core is an object-relational mapping (ORM) framework for .NET, that allows developers to work with databases using object-oriented concepts.

It simplifies database operations by enabling developers to interact with the database using familiar things such as classes, objects, and LINQ (Language-Integrated Query). Entity Framework Core supports various database providers and allows for the creation, retrieval, modification, and deletion of data without the need to write complex SQL queries manually. It also offers many features that make it an efficient tool for building data-driven applications in . NET.

## site.Data Seeding

data seeding is a process of inserting an initial set of data into the database.

It can be accomplished in several in EF Core:

Model seed data: where the data is associated with an entity type in the model configuration

Manual migration customization: where explicit calls to InsertData(), UpdateData(), and DeleteData() are added to the migration

Custom initialization logic: where DbContext.SaveChanges() is used before the main application logic to seed the data

The choice of which way to use depends on the application requirements and constraints.

Links to an external site.User secrets
In .NET Core, User secrets provide a secure way to store sensitive user information separately, such as API keys and connection strings.

By enabling user secrets, we can store this confidential data in a secrets.json file, which is not uploaded to source control.

It can be easily managed through Visual Studio, and the stored secrets can be accessed in the application using the IConfiguration interface.

## User Secrets to .NET Core

User secrets : is a secure way of storing private user information such as API keys, client secrets, and connection strings.

- Never store passwords or other sensitive data in source code.
- Production secrets shouldn't be used for development or test. Secrets shouldn't be deployed with the app  

- nvironment variables : Environment variables are used to avoid storage of app secrets in code or in local configuration files. Environment variables override configuration values for all previously specified configuration sources.

- Secret Manager: The Secret Manager tool stores sensitive data during the development of an ASP.NET Core project. a piece of sensitive data is an app secret.

### Things I want to know more about

the whole process beacause the tutorial was hard understand and knowing the best practices of Entity Framework.

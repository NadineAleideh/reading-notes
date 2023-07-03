# Class 07 Readings: Collections & Enums

## Collections

A collection is a class, and it's a ways to create and manage a group of related objects.

## Why this topic matters

- Collections provide a more flexible way to work with groups of objects. Unlike arrays, the group of objects you work with can grow and shrink dynamically as the needs of the application change. For some collections, we can assign a key to any object that you put into the collection so that we can quickly retrieve the object by using the key.

- Enumerations are commonly used to represent a set of related values or options. They can improve code readability and maintainability by providing meaningful names instead of using raw integers or strings. You can use them in switch statements, method parameters, properties, and more.

## collection Types

1. **Generic** : If the collection contains elements of only one data type, we can use one of the classes in the **System.Collections.Generic** namespace. A generic collection enforces type safety so that no other data type can be added to it. When we retrieve an element from a generic collection, we do not have to determine its data type or convert it.

2. the collections in the S**ystem.Collections.Concurrent** namespace provide efficient thread-safe operations for accessing collection items from multiple threads.

3. The classes in the **System.Collections** namespace do not store elements as specifically typed objects, but as objects of type Object.

## Enumeration types ("also called enums")

 An enumeration type is a user-defined data type that consists of a set of named integral constants, known as enumeration members. These members represent a distinct set of values that the enumeration type can take and assigned to a variable.

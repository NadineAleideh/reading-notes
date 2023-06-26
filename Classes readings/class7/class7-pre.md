# Class 07 Readings: Interfaces

## Interfaces

Interfaces tell a class what it can do. This means that when you visually see an interface implemented onto a class, that means that the class you are looking at has an obligation to fulfill the requirements listed in the interface.

## Why this topic matters

Interfaces are essential because they:

1. Define a contract that classes must adhere to.
2. Enable polymorphism and code reusability.
3. Support multiple inheritance of behavior.
4. Promote loose coupling and modularity.
5. Enhance testability and flexibility in software design.

## Interface Properties

- An interface is like an abstract base class with abstract methods, but is not. Any class or struct that implements the interface must implement all its members.
- An interface can't be instantiated directly. Its members are implemented by any class or struct that implements the interface.
- Interfaces can contain events, indexers, methods, and properties.
- Interfaces contain no implementation of methods.
- A class or struct can implement multiple interfaces. A class can inherit a base class and also implement one or more interfaces.

# Readings Class 04: Classes & Memory Management

- What’s the difference between a static and an instance constructor?

  A static constructor is used to initialize static members of a class, and it's executed only once when the class is accessed for the first time. An instance constructor, on the other hand, is used to create and initialize individual instances of a class and is called whenever a new object is created using the class.

- How does the use of a static constructor differ from setting properties/values?

  A static constructor is used to initialize static members of a class, while setting properties/values is used to initialize specific instance members of an object. Static constructors run once for the entire class, ensuring that static members are initialized before they are accessed. But Setting properties/values allows you to customize the initial state of individual objects by assigning specific values to their instance members.
- Knowing what you now know about the stack and the heap, how might you rethink the way you did projects in previous courses, to make more effecient use of memory?

  I will pay attenstions to Choosing appropriate data structures and algorithms that optimize memory usage, trying to minimize unnecessary memory allocations by reusing objects, using value types when appropriate, and using data structures with fixed sizes instead of dynamic ones when possible, Releasing unused resources and utilizing garbage collection.

- Compare “Garbage Collection” in C# with the lifecycle of normal household items.

  The process of acquiring items, duration of using these items , disposing when these items are no longer needed  in household items similar to the lifecycle of objects in C# with the added benefit of automatic memory management through garbage collection, so GC is automatically identifies objects that are no longer in use and frees up the memory they occupy.

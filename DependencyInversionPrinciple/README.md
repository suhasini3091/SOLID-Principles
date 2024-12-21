Dependency inversion principle
Dependency inversion principle (DIP) states to depend upon abstractions, [not] concretes.

Importance
Loose coupling: Reduces dependencies between modules, making the code more flexible and easier to test.
Flexibility: Enables changes to implementations without affecting clients.
Maintainability: Makes code easier to understand and modify.[8][7]

Dependency Inversion states that - High level modules should not depend on low level modules but instead both of them should depend on Abstractions
Abstractions should not depend on the details. Concrete implementations should depend on abstractions. Interfaces are a way of doing DI well
It should not depend on what gets done but just that it gets done

By dictating that both high-level and low-level objects must depend on the same abstraction, this design principle inverts the way some people may think about object-oriented programming.


This is going to cover territory that it is DI

Dependency Inversion is one of the principle
Dependency Injection is one of the implementations of the principle
But can also dynamically change the instances


Make a change to the application using 1 piece, we are not dependent on that instantiation

Application is not 1 big monolithic application but really small chunks, things that only 1 thing

SOLID - takes us into tiny little parts, things that are tiny little interfaces which we can plug and unplug, I don’t have to change the whole thing. 
I can tweak small changes to apply to the whole application
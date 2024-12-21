
Interface segregation principle (ISP) states that "[c]lients should not be forced to depend upon interfaces that they do not use."


Decoupling: Reduces dependencies between classes, making the code more modular and maintainable.
Flexibility: Allows for more targeted implementations of interfaces.
Avoids unnecessary dependencies: Clients don't have to depend on methods they don't use.

Interfaces states that we should have these methods but if they don’t apply to the client referencing it, then we should not implement it
We create interfaces that are modular enough so that they are flexible enough, future proof
It can create multiple files but establishiing modularity but its very easier to manage with correct naming conventions
It explains the principle that we don’t have a single monolithic interface that doesn’t apply to everything that implements it, instead we break the interface 
into pieces and match them together in a modular way
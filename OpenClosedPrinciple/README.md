	## Open to extension but Closed for modification

	Open–closed principle (OCP) states that "[s]oftware entities ... should be open for extension, but closed for modification."[4]

* *Extensibility: New features can be added without modifying existing code.
* *Stability: Reduces the risk of introducing bugs when making changes.
* *Flexibility: Adapts to changing requirements more easily.
	
	• Minimized Risk of Bugs: By following OCP, existing code remains unaltered when new features are added. This significantly reduces the risk of introducing bugs into already tested and proven code, ensuring stability and reliability.
	• Increased Reusability: Components designed to be extended (but not modified) can be reused across different parts of the application or even in different projects.
	• Improved Maintainability: Since the core functionality of existing modules does not change, maintaining the application becomes simpler. Modifications are made by adding new code rather than changing the old one, which helps in maintaining a clean and organized codebase.
	• Use of OOPs Concept Effectively: Applying OCP often leads to the use of interfaces and abstract classes, promoting the use of inheritance and polymorphism (OOP Concepts). This results in a more flexible and dynamic architecture, where behavior can be changed dynamically at runtime.
	
	
	• Interfaces allow us to change actual implementation
	• This is a contract and has a create method
	
	• A class should have the Ability to be closed for modification BUT open for extension
     If its working, don’t introduce potential new bugs into the system
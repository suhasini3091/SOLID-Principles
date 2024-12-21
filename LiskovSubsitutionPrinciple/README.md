Liskov substitution principle (LSP) states that "[f]unctions that use pointers or references to base classes must be able to use objects of derived classes without knowing it."[5] See also design by contract.[5]

Importance
Polymorphism: Enables the use of polymorphic behavior, making code more flexible and reusable.
Reliability: Ensures that subclasses adhere to the contract defined by the superclass.
Predictability: Guarantees that replacing a superclass object with a subclass object won't break the program.[5]


	• Covariance - taught about Changing the return type
	• Contravariance - taught about changing the input type 
	• Preconditions, postconditions - 
		Preconditions - cannot weaken preconditions
		Postconditions - cannot weaken postconditions
	• Cannot change how the base functions change radically

	• How to solve the issue that a child class (which is actually a parent class) 
still has inheritance but at the same time is complaint with LSP
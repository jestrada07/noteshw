Solid Principles-
Code Fragility: 
Fragility is the tendency of the software to break in many places every time it is changed
Technical Debt- The cost of prioritizing fast delivery over code quality for long periods of time. The Choice You Have to Make: Fast delivery - Easiest fix/change, Poor written code. Code quality- Takes more time, Adds a bit of complexity, Maintainable. Some Technical Debt Facts: No matter how good the team is, technical debt will accumulate over time Left uncontrolled, it will kill your project. The key is to keep it under control. Solid stands for -Single Responsibility Principle, Open Closed Principle, Liskov Substitution Principle, Interface Segregation Principle, Dependency Inversion Principle. Benefits of solid : Easy to understand and reason about. Changes are faster and have a minimal risk level.Highly maintainable over long periods of time. Cost effective. 
The open closed Principle: modifying existing code could be dangerous, not a good idea. The open closed principle states that classes, functions, and modules should be closed for modification but open for extension. But what does closed for modification and open for extension really mean? Well, a class is closed for modification if for each feature that we need to add, we do not touch an existing source code. The source code basically becomes immutable.
Changing requirements are inevitable
Inheritance and design patterns are
effective ways to add features without
modifying existing components. OCP also applies to packages. Sometimes it is not pragmatic to extend a component and we have to modify it. Making a flexible design adds more. 
complexity. LSP : Don't think relationships in terms of "IS A" Empty methods, type checking and hardened preconditions are signs that you are violating the LSP. SP also applies for interfaces, not just for class inheritance. Most times you fix an incorrect type hierarchy by breaking it. Real life categories do not always map to OOP relationships. ISP: The ISP is linked with the LP and SRP. Don't confuse the word"interface" in the name with a Java interface. Pay attention to the symptoms of large
interfaces and take action. Break large interfaces into many focused ones for code that you own. Use the "Adapter Pattern" for external code. DIP: The ISP is linked with the LP and SRP. Don't confuse the word "interface" in the name with a Java interface. Pay attention to the symptoms of large interfaces and take action. Break large interfaces into many focused ones for code that you own. Use the "Adapter Pattern" for external

Design patterns: A reusable and named solution to a recurring problem in a context.OOP principles SOLID Single responsibility Open-closed Liskov substitution Interface segregation Dependency injection Other Don't repeat yourself Encapsulate what changes Favor composition over inheritance. Programming to interfaces. Pattern classification : Purpose, Creational, Behavioral, Structural, Scope, Class, 
Object. The Strategy Pattern Is a Mix Of: Encapsulating what changes, Favoring composition over inheritance.Open-close principle . Programming to interfaces. Patterns capture expert knowledge. Reuse that knowledge Find the appropriate design. Shared and precise vocabulary. Inheritance is not always the best solution - Composition can offer a more flexible alternative. Patterns can guide you. Singleton - Ensures a class only has one instance,providing a global point of access
Factory Method - Allows subclasses decide which class to instantiate. Abstract Factory -  Creates hierarchies or families of related objects. Builder- Separate the construction of an object from its representation. Facade- Simplifies an interface to a subsystem, decoupling a client from it. Decorator-  Attach additional responsibilities to an object dynamically.
Adapter- Convert the interface of a class into another interface clients expect.Proxy - Provides a surrogate for another object to control access to it. 

Chapter 13 test automation- Abstraction: Templates Abstract classes and methods are templates that are meant to be implemented by their subclasses . Reserved Word
Classes and methods are declared abstract by
Implementation Required on Inheritance
If a subclass extends from an abstract class, it
must implement its abstract methods, or be
Abstract Classes. Abstract Classes  cannot be instantiated. Is to be used as a superclass. If even one method in a class is abstract, the class must be declared. Interface: Not for Instantiation
Interfaces cannot be instantiated Implement Interfaces are Abstract if not Implemented
An Class that implements an interface, must
implement all of its methods or it must declare
itself abstract.  Abstract Methods: methods in an interface must be abstract(explicit declaration needed) or default. 
Risky Behavior - Chapter 11: A method can throw an exception when something goes wrong at runtime.An exception is always an object of type exception.
The compiler does not enforce handling of exceptions that are of type RuntimeException. They do not need to be declared or wrapped in a try/catch block.
To throw an exception in a method, the "throw" keyword is used, followed by a new exception object.


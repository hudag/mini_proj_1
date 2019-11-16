# Mini Proj 2 Terms


## How Python uses Indentation to Control Flow
    
  * Control flow in your code is when the order that your program is executed is affected. Python uses whitespace to delimit scope. Each block must start with the same amount of whitespace (one or more). For example if you have a for loop in mython the code you wish to have a part of the for loop needs to be indented. 
    
  * Here is an example of the use of the for loop with the proper use of whitepace.

      ![forloop](/images/forloop.jpg)

## Don't Repeat Yourself
  * This is a practice that aims to make sure a programmer does not repeat code, repition of code is wasteful. It reduces the repition of software patterns. 
  * Here is an example of using/not using DRY programming practices.

      ![dry](/images/dry.PNG)

## Design Patterns from Gang of Four
  * The gang of four are the authors of the book Design Patterns: Elements of Reusable Object-Oriented Software.
  * Their design patterns are as follows:
    * Creational
      * Abstract Factory. Allows the creation of objects without specifying their concrete type.
      * Builder - Uses to create complex objects.
      * Factory Method - Creates objects without specifying the exact class to create.
      * Prototype - Creates a new object from an existing object.
      * Singleton - Ensures only one instance of an object is created.
    * Structrual
      * Adapter - Allows for two incompatible classes to work together by wrapping an interface around one of the existing classes.
      * Bridge - Decouples an abstraction so two classes can vary independently.
      * Composite - Takes a group of objects into a single object.
      * Decorator - Allows for an object’s behavior to be extended dynamically at run time.
      * Facade - Provides a simple interface to a more complex underlying object.
      * Flyweight - Reduces the cost of complex object models.
      * Proxy - Provides a placeholder interface to an underlying object to control access, reduce cost, or reduce complexity.
    * Behavior
      * Chain of Responsibility - Delegates commands to a chain of processing objects.
      * Command - Creates objects which encapsulate actions and parameters.
      * Interpreter - Implements a specialized language.
      * Iterator - Accesses the elements of an object sequentially without exposing its underlying representation.
      * Mediator - Allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
      Memento. Provides the ability to restore an object to its previous state.
      * Observer - Is a publish/subscribe pattern which allows a number of observer objects to see an event.
      * State - Allows an object to alter its behavior when its internal state changes.
      * Strategy - Allows one of a family of algorithms to be selected on-the-fly at run-time.
      * Template Method - Defines the skeleton of an algorithm as an abstract class, allowing its sub-classes to provide concrete behavior.
      * Visitor - Separates an algorithm from an object structure by moving the hierarchy of methods into one object.
## Class
  * A class is a code template for creating objects. In python a class is created by the keyword class. A bluebring for an object.
  * For example to make a class you would do **class Name:**

## Object
  * Objects are the basic run-time entities in an object-oriented system. They may represent a person, a place, a bank account, a table of data or any item that the program must handle. When a program is executed the objects interact by sending messages to one another. They includ eattributes and methods.
  * For example to make an object you would do **p1 = MyClass()**



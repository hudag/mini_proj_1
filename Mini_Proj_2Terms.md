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

## Static
  * When a variable is declared as static, then a single copy of variable is created and shared among all objects at class level. Static variables are, essentially, global variables. All instances of the class share the same static variable.
  * The most common example of this is: **public static void main(String[] args){}** as seen in java.
  * In Python anything that you declare is a static variable like **f=0** in a class.

## Property / Attribute
  * Attributes are described by data variables for example like name, age, height. 
  * Properties are special kind of attributes which have getter, setter and delete methods like get, set and delete methods. In Python, you can define getters, setters, and delete methods with the property function.

## Method
  * A method is a function that “belongs to” an object. (In Python, the term method is not unique to class instances: other object types can have methods as well. For example, list objects have methods called append, insert, remove, sort, and so on.

## Exception
  * An exception is an event, which occurs during the execution of a program that disrupts the normal flow of the program's instructions. In general, when a Python script encounters a situation that it cannot cope with, it raises an exception. An exception is a Python object that represents an error.
  * For example this is an expection error **ZeroDivisionError** when you try to divide by 0.

## Unit Test
  * The first level of software testing where the smallest testable parts of a software are tested. This is used to validate that each unit of the software performs as designed.
  * An example of a Unit Test in Python
      ```python
      import unittest 
        
      class SimpleTest(unittest.TestCase): 
        
          # Returns True or False.  
          def test(self):         
              self.assertTrue(True) 
        
      if __name__ == '__main__': 
          unittest.main() 
      ```

## Constructor
  * A constructor is a special kind of method that Python calls when it instantiates an object using the definitions found in your class. Python relies on the constructor to perform tasks such as initializing (assigning values to) any instance variables that the object will need when it starts.
  * Here are examples of 2 types of constructors
        ![def](/images/defc.PNG)
        ![para](/images/parc.PNG)

## Factory
  * Factory method is a creational design pattern which solves the problem of creating product objects without specifying their concrete classes. Factory Method defines a method, which should be used for creating objects instead of direct constructor call (new operator).
  * An example of how it works:
      ![fac](/images/fac.PNG)

## Decorator
  * Decorators are very powerful and useful tool in Python since it allows programmers to modify the behavior of function or class. Decorators allow us to wrap another function in order to extend the behavior of wrapped function, without permanently modifying it.
  * Example of a Decorator:
      ![dec](/images/dec.PNG)


## Extend Class 
* Means to add a new methods and not change the existing one. Makes it more functional, it can be done by having a child class. 

![extend](/images/extend.PNG)

## CSV Files
* A Comma Separated Values (CSV) file is a plain text file that contains a list of data
![csv](/images/csv.PNG)

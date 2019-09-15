# OOAD_Design_Principles

Following are the OOAD principles: 
1. Single Responsibility Principle [SRP]: 
  The S in SOLID. 
  An entity (class or a method) should have one task it is supposed to do. By having a single entity do multiple tasks or even have multiple behaviors, we end up in complex and difficult to maintain code. So, just KEEP IT SIMPLE SILLY! 
  
2. Open Close Principle
  The O in SOLID. 
  The classes should be open for extension but closed for changes. Generalization, abstraction and interfaces provide a way to extend classes. 
  Advantages: 
  a. Loosely coupled systems. 
  b. High maintainance 
  
3. Liscov's Substitution Principle [LSP]:
  The L in SOLID. 
  If a class S is a subclass of class B, then S should be able to replace all instalces of B without changing behaviors of the program. 
  It does not imply that the subclasses should replace the base class, but provides a way to check if the inheritance is correct. 
  
4. Interface Segregation: 
  The I in SOLID. 
  Sometimes, the interfaces get overloaded with behaviors which result in all or some of its concreate classes end up having few methods that are not applicable to it. These are the dummy methods. 
  Solution? Split or segregate the interfaces to solve this problem. 
  A class should not be forced to depend on methods it does not need or use. Do not let your classes have dummy methods. 
  
5. Dependency Inversion: 
  The D in SOLID. 
  Depend on generalizations and not low level concrete classes. 
  
6. Composing Objects Principle: 
  Prefer composition over inheritance to acheive low coupling and code reuse. 
  
7. Dont Repeat yourself (DRY): 
  Code reuse over code duplication. 
  
8. Encapsulate what varies. 

9. Program to interface and not implementation. 

10. Delegate to other classes. [Goes inline with single responsibility principle]

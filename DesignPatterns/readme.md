# Design Patterns
## Object Creation
### Builder
To avoid using complex constructor and too much arguments, use a Builder class to initialize object of specified type and set variables.
Build certain type of objects, seperate construction from representation. 
### Factory
Create instances of certain class's subclasses. 
### Prototype
Using clone method(possibly with copy constructor).
### Singleton
Global instance, instantiate once.
## Structure
### Adapter
Adapter inherits class A and has class B object as variable, then it can use B as A.
### Bridge
Separate interface from implementation. Pass and save implementation class, call when need. 
### Composite
Use objects and other composite to form tree structure.
### Decorator
Inherit base or other decorator(as base), like wrapping, attach additional behavior or responsibilities.
### Facade
Use one single interface that calls functions of other classes in a system.
### Flyweight
Share properties(maybe using static and access with index) across objects to save memory. 
## Behavior
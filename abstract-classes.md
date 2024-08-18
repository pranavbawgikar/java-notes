## Abstract Classes
Abstract classes in Java act as a boundary between the implementation method and its functionality. It is used to exchange the functionality between the concrete class members and the abstract class method.

Rules for Abstract Classes in Java
1. It cannot be instantiated.
2. It can final methods.
3. An abstract class must be declared using abstract keyword.
4. It can have abstract and non-abstract methods.
5. It can have constructors and static methods also.

### Abstract Class vs. Interface

| **Abstract Class**                                                   | **Interface**                                                     |
|----------------------------------------------------------------------|-------------------------------------------------------------------|
| Abstract classes can have abstract and non-abstract methods.         | Interface can have only abstract methods.                         |
| Abstract classes include non-final variables.                        | Interface has only final variables.                               |
| Abstract classes have static, non-static, final, and non-final variables. | Interface has static and final variables only.                    |
| Abstract classes can implement an interface.                         | Interface cannot implement an abstract class.                     |
| Abstract classes are implemented using the `extends` keyword.        | Interface is implemented using the `implements` keyword.          |
| Abstract classes can extend Java classes and interfaces.             | Interface can extend only another interface.                      |
| Members can be private and protected in an abstract class.           | Members are public by default in an interface.                    |

What is Interfaces?
1)Interface is a keyword that is used to acheive multiple inheritence.It is just like a class that is used to hold constant variable and fully abstract method.
A constant variable that can never change and syntax is like:   public static final int k;
fully abstract method means a method which does not have body like:  public abstract void football();
You can never create instance of an interface because interface can not have any constructor.
Interface is always having public property.Interface can used by inheritence only.
A class can implements one or more than one interface seperated by , .
class X implements Y,Z{}
where Y and Z is an Interface.
An Interface can extends one or more than one interface seperated by , .
interface X extends Y,Z{}
where Y and Z is an interface.
A class can extends another class an also implements one or more than one interface.
class X extends Y implements Z,K{}
where Y is a class and Z,K is an interface.
Interface can never be made final.Interface can be abstract.
We can acheive loose coupling using interface.Interface can never extends or implements a class.
A marker interface is an interface that has nothing like Cloneable, Serializable etc.
We can never use super keyword in case of interface.
All interface methods body provided by its sub class using overriding.

JDK 1.8 Features
In an interface we can define a non static method using default keyword.We can also define static method inside an interface.
We can use super keyword in case of interface using interface name.

What is Functional Interface ?
An interface which have single abstract method only.It can have defined method also.

What is Lambda Expression ?
Lambda Expression is an expression to optimize the code.It apply only with functional interface.It can be no parameterized or parameterized.
Syntax is like :
()-> System.out.println("No Parameterized");
Syntax is like :
(x)-> System.out.println("Parameterized");
JDK 1.9 Features
In an interface you can have private methods.

Abstraction in Java
Hiding the complexity and showing the functionality to the user that is called Abstraction.
Using abstract class we can acheive Abstraction.
An example is shown in the above code file. 

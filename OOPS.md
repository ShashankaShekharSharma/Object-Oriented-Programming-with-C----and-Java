# **Object Oriented Programming**

A computer programming model that organizes software design around data or objects rather than function or logic.

A **Object** has unique attributes and behavior

**OOP** focuses on objects that developers want to manipulate rather than the logic required to manipulate them.

-   well-suited for programs that are large, complex and actively updated or maintained.

-   Develop programs for manufacturing and design as well as mobile application. OOP can be used for manufacturing system simulation software.

It is the way of writing computer programs using the concepts of objects which are like building blocks that represent the real world things. It helps to *organize the code neatly making* it reusable and easy to manage

# Aim of OOP:

-   Bind together the data and functions that operate on them so that no other part of the code can access this data except that function.

# Key Concepts of Object Oriented Programming

**Objects** Objects are instances of classes and represent real world entities. They encapsulate data and behavior related to the entity they model. These are instances of a class created with specifically defined data.

**Class** is an user-defined data types that act as the blueprint for individual objects, attributes and methods.

**Encapsulation** Encapsulation involves bundling data methods that operate on the data into a single unit called class. This hides the internal details of an object and allows access only through well defined interfaces

-   All information is contained inside an object and only select information is exposed

-   The implementation and state of each object are privately held in a defined class

-   Other objects do not have access to this class or authority to make changes. They are only able to call a list of public functions or methods

-   This characteristic of hiding data hiding provides greater security and avoids unintended data corruption

**Inheritance** Enables the creation of new classes that inherit attributes and behaviors from existing classes. It promotes code reuse and the establishment of hierarchy of classes

-   Classes can reuse code from other classes

-   forces more through data analysis, reduces development time and ensures a high level of accuracy

# **Key Principles of Object Oriented Programming**

**Polymorphism** It allows objects to be treated as instances of their parent classes, enabling flexibility in code design. It includes method overloading and method overriding.

-   Object are designed to share behaviors and they can take on more than one form

-   The program will determine which meaning or usage is necessary for each execution of that object from a parent class, reducing the need to duplicate code

-   A child class is then created which extends the functionality of the parent class

-   It allows different types of objects to pass through the same interface

**Abstraction** involves simplifying complex systems by modelling classes based on their essential properties. If focuses on what an object does rather than how it achieves its functionality.

-   Objects only reveal internal mechanisms that are relevant for the use of other objects, hiding any unnecessary implementation code

-   The derived class can have its functionality extended

-   This concept can help developers more easily make additional changes or additions over time.

**Modularity** modularity is the breaking down a system into a smaller, manageable units (classes) wherein each class encapsulates specific set of functionalities making the code more organised and maintainable.

**Reusability** creation of reusable components through classes and inheritance reducing redundancy and promoting efficient code reuse across different parts of an application

# **Benefits of Object Oriented Programming**

1.  It allows developers to reuse the existing code leading to faster development cycles
2.  Large and complex codes becomes easier to maintain and update code
3.  Provides a flexible and scalable framework that supports the growth and adaptation of software over time
4.  Makes the code intuitive and helps in building effective software design

-   Once an object is known, it is labelled with a class of objects that defines the kind of data it contains and any logic sequences that can manipulate it. Each distinct logic sequence is known as a method.

-   Objects can communicate with well-defined interfaces called messages.

-   **Modularity:** Encapsulation enables objects to be self contained, making, troubleshooting and collaborative development easier.

-   **Reusability:** Code can be reused through inheritance, meaning a team does not have to write the same code multiple times.

-   **Productivity** Programmers can construct new programs quicker through the use of multiple libraries and reusable code

-   **Easily upgradable and scalable:** Programmers can implement system functionalities independently

-   **Interface Descriptions:** Descriptions of external systems are simple, due to message passing techniques that are used for objects communication.

-   **Security:** Using encapsualtion and abstraction, complex code is hidden, software maintenance is easier and internet protocols are protected.

-   **Flexibility:** It enables single function to adapt to the class it is placed in. Different objects can also pass through the same interface

# Procedural Programming:

procedures or functions that performs operations on the data

# Object Oriented Programming:

creating objects that contain both data and functions

# Advantages of OOP over Procedural:

-   Faster and easier to execute

-   Provides a clear structure for programs

-   Makes the code easier to maintain, modify and debug

-   Created full reusable code applications with less code and shorter development time

# Methods

-   functions that are defined in a class that describes the behaviours of an object

-   each method contained in class definitions starts with a reference to an instance object.

-   the subordinates contained in an object are called instance methods

# Attributes

-   represents the state of an object

-   Objects will have data sorted in the attributes field

-   Class attributes belong to the class itself

# Examples of OOP Language

-   Simula is the first Object-Oriented Programming language

-   Popular OOP languages include Ruby, Scala, JADE, Emerald

-   Programming languages designed primarily for OOP include Java, Python, C++

-   Other Programming Languages that pair with OOP Include VisualBasic.NET, PHP, JavaScript

# Criticism of OOP

OOP emphasizes the data component of software development and does not focus enough on computation and algorithms.

It may be more complicated to write and can take longer to compile

# Alternative Methods to OOP

1.  Functional Programming:

    This includes languages such as Erlang and Scala which are used for telecommunications and fault tolerant systems

2.  Structured or Modular Programming:

    This includes languages such as PHP and C#

3.  Imperative Programming:

    This is alternative to OOP which focuses on function rather than models and includes C++ and Java

4.  Declarative programming:

    This programming method involves statements on what the task or desired outcome is but now how to achieve it. Language include Prolog and Lisp

5.  Logical Programming:

    This method is based mostly in formal logic and uses languages such as Prolog contains set of sentences that express facts or rules about a problem domain. It focuses on tasks that can benefit from rule based logical queries

    *Most Advanced Programming languages enables developers to combine models because they can be used for different programming methods. JavaScript can be used for OOP and functional programming*

    | Flag            | Bit-Field        | Usage                                      | Purpose                                                               | Comment                                                                                                  |
    |---------------|---------------|---------------|---------------|---------------|
    | ios::left       | ios::adjustified | cout.setf(ios::left,ios ::adjustified)     | For left justified output                                             | If no flag is set then by default, the output will be right justified                                    |
    | ios::right      | ios::adjustified | cout.setf(ios::right,ios::adjustifield)    | For right justified output                                            |                                                                                                          |
    | ios::internal   | ios::adjustified | cout.setf(ios::internal, ios::adjustified) | Left justify sign or base indicator and right- justify rest of number |                                                                                                          |
    | ios::scientific | ios::floatfield  | cout.setf(ios::scientific,ios::floatfield) | For scientific notation                                               | If no flag is set then any of two notations can be used for point numbers depending on the decimal point |
    | ios::fixed      | ios::floatfield  | cout.setf(ios::scientific,ios::floatfield) | Left justify sign or base indicator and right- justify rest of number | If no flag is set then any of two notations can be used for point numbers depending on the decimal point |
    | ios::dec        | ios::basefield   | cout.setf(ios::fixed,ios::floatfield)      | Left justify sign or base indicator and right- justify rest of number | If no flag is set then any of two notations can be used for point numbers depending on the decimal point |
    | ios::oct        | ios::basefield   | cout.setf(ios::scientific,ios::floatfield) | Left justify sign or base indicator and right- justify rest of number | If no flag is set then any of two notations can be used for point numbers depending on the decimal point |
    | ios::hex        | ios::basefield   | cout.setf(ios::scientific,ios::floatfield) | Left justify sign or base indicator and right- justify rest of number | If no flag is set then any of two notations can be used for point numbers depending on the decimal point |

***Question:***

Write a C++ program to construct the following pattern, using a nested loop number.\
Expected Output:\
999999999\
88888888\
7777777\
666666\
55555\
4444\
333\
22\
1

``` cpp
#include<iostream>
using namespace std;
int main(){
  for(int i = 9;i>=1;i--){
    for(int j = 1;j<=i;j++){
      cout<<i;
    }
    cout<<endl;
  }
  return 0;
}
```

# Variables

Content of memory location that stores a certain value. A certain variable is identified or denoted by a variable name.

*Rules*

-   A variable name can have one or more letters or digits or underscore

-   white space or punctuation symbols are not allowed

-   must begin with a letter

-   cannot be keyword or any reserved word

-   Data C++ is a case-sensitive language

## Types of variables

-   Local Variables

    ``` cpp
    public class Car{
    public: 
      void display(int m)
    };
    ```

-   Instance Variables

    -   Belongs to an instance or object of a class

    -   Each instance of a class has its own copy

    -   Exists as long as the object exists

    -   Declared within a class but outside any function

-   Static Variables

-   Constant Variables

# Datatypes of C++

A Type defines a set of values and a set of operations that can be applied on those value. The set of values for each type is known as the domain for the type

DataTypes in C++ is mainly divided into two types:

1.  Primitive Data Types:
    -   Integer

    -   Character

    -   Boolean

    -   Floating Point

    -   Double Floating Point

    -   Valueless or Void

    -   Wide Character

    -   String
2.  Abstract or User Defined Data Type:
    -   **Basic Data Types**

        -   Integer

        -   Char

        -   Float

        -   Double

        -   Void

    -   **Derived Data Types**

        -   Pointers

        -   Functions

        -   References

        -   Arrays

    -   **User Defined Data Types**

        -   Structure

        -   Class

        -   Union

        -   Enumeration

        -   Typedef

# UML

-   It is not a programming language but a visual language

-   It is used to portray the behaviour and structure of the system

-   The Object Management Group (OBG) adopted Unified Modelling Language as a standard in 1997

-   The International Organisation for Standardization published UML as an approved standard in 2005

-   UML becomes essential to communicate essential requirements, functionalities and processes of the system

## Classification of UML

1.  Structural Diagram

-   Capture static aspects or structure of the system
-   Component Diagrams, Object Diagrams, Class Diagrams and Deployement Diagrams

2.  Behaviour Diagram

-   Capture Dyanamic aspect
-   Use Case Diagrams, State Diagrams, Activity Diagrams and Interaction Diagrams

## Use case Diagrams

-   Use to model the high level functions and scope of the system
-   Helps to find the interactions between the system and its actors
-   The Use cases and its actors in use case diagrams describe what the system does and how the actors use it but not how the system operates internally.

### Elements of Use Case Diagrams

#### Use Cases

-   A use case describes a function that a system performs to achieve the user's goal. A use case must yield an observable result that is of value to the user of the system.

#### Actors

-   An actor represents the role of a user that interacts with the system that you are modelling.

#### Subsystems

-   subsystems are type of stereotypes components that represent independent units in a system.
-   It is used in class, componenets and use case diagrams to represent large scale components in the system that is being modelled

#### Relations in Use Case Diagrams

-   Connection between model elements

-   It is a type of model element which adds semantics to a model by defining the structure and the behaviour between model elements

## Steps for making Use Case Diagram

1.  Analyze the whole system before starting
2.  Find the system functionalities
3.  List the actors that interact with the system
4.  Identify the relation between the actor and the use case
5.  An actor can interact multiple times with a use case or system at a particular instance of time

### View Items

-   It is further extended by several use cases such as:\
    Search Items, Browse Items, View Recommended Items, Add to Shopping Cart, Add to Wish List

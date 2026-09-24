# Object Oriented Programming with C++
## Practical Programs – Unit III

### Student Information

| Field | Details |
|---------|---------| 
| Student Name | Shravani Thakur|
| PRN | 125UAD1098 |
| Class/Division | SY.Btech / A |
| Course Name | Object Oriented Programming using C++ |
| Unit | Unit III – Operator Overloading & Polymorphism |


Unit I – C++ Fundamentals and Basic OOP Concepts

Overview

This unit contains a collection of introductory C++ programs designed to build a strong foundation in programming and Object-Oriented Programming. The programs progress from basic data types and decision-making statements to arrays, functions, classes, constructors, destructors, static members, inline functions, and friend functions.

These practical programs help students understand the basic syntax and programming structure of C++ before moving toward advanced OOP concepts such as inheritance, polymorphism, abstraction, and operator overloading.

List of Programs

1. Basic Data Types

File: 01_basic_data_types.cpp

Description

Demonstrates the declaration and use of fundamental C++ data types such as int, char, and float.

Concepts Covered

Integer data type

Character data type

Floating-point data type

Variable declaration

Console output using cout

Learning Outcome

Students learn how to declare variables of different data types and display their values.

2. If-Else Statement

File: 02_if_else.cpp

Description

Demonstrates decision-making using the if-else conditional statement. The program checks whether marks satisfy the passing condition.

Concepts Covered

Conditional statements

if

else

Relational operators

Decision making

Learning Outcome

Students understand how a C++ program makes decisions based on conditions.

3. Loop and Array

File: 03_loop_and_array.cpp

Description

Demonstrates the creation of an integer array and uses a for loop to access and display its elements.

Concepts Covered

Arrays

Array initialization

for loop

Array indexing

Iteration

Learning Outcome

Students learn how to store multiple values in an array and process them using loops.

4. Functions

File: 04_functions.cpp

Description

Demonstrates the declaration, definition, and calling of a user-defined function. The program calculates the sum of two numbers.

Concepts Covered

Function declaration

Function definition

Function parameters

Return values

Function calling

Learning Outcome

Students understand how functions improve code organization, reusability, and readability.

5. Class and Object

File: 05_class_and_object.cpp

Description

Introduces the fundamental concepts of Object-Oriented Programming by creating a Student class and an object of that class.

Concepts Covered

Class

Object

Data members

Member functions

Object member access

Learning Outcome

Students learn how classes act as blueprints for objects and how objects access class members.

6. Constructor and Destructor

File: 06_constructor_and_destructor.cpp

Description

Demonstrates the use of a constructor and destructor in a C++ class. The constructor executes when an object is created, while the destructor executes when the object is destroyed.

Concepts Covered

Constructor

Destructor

Object creation

Object destruction

Automatic lifecycle management

Learning Outcome

Students understand how constructors initialize objects and how destructors perform cleanup when objects go out of scope.

7. Static Member

File: 07_static_member.cpp

Description

Demonstrates a static data member that is shared by all objects of a class. The program counts the number of Student objects created.

Concepts Covered

Static data members

Shared class-level data

Object counting

Scope resolution operator

Learning Outcome

Students understand the difference between ordinary data members and static members shared across all objects.

8. Inline and Friend Function

File: 08_inline_and_friend_function.cpp

Description

Demonstrates both an inline member function and a friend function. The friend function accesses the private data member of the class.

Concepts Covered

Inline functions

Friend functions

Private data members

Access control

Member functions

Learning Outcome

Students understand how inline functions can be used for small operations and how friend functions can access private members of a class.

Concepts Covered

No.

Concept

Program

1

Basic Data Types

01

2

Conditional Statements

02

3

Arrays

03

4

Loops

03

5

Functions

04

6

Classes and Objects

05

7

Constructors

06

8

Destructors

06

9

Static Members

07

10

Inline Functions

08

11

Friend Functions

08

Learning Objectives

After completing this unit, students should be able to:

Understand the basic syntax and structure of C++ programs.

Work with fundamental C++ data types.

Use conditional statements for decision-making.

Implement loops and arrays.

Create and use user-defined functions.

Understand the basic structure of classes and objects.

Implement constructors and destructors.

Understand static class members.

Use inline functions for simple operations.

Understand the purpose and implementation of friend functions.

Build a foundation for advanced Object-Oriented Programming concepts.

Software Requirements

C++ compiler

GCC / MinGW / Clang / MSVC

Visual Studio Code or any C++ compatible IDE

C++11 or later recommended

How to Compile and Run

Using GCC:

g++ filename.cpp -o output
./output

Example

g++ 05_class_and_object.cpp -o class_object
./class_object

On Windows, the executable can be run as:

class_object.exe

Repository Structure

Opp-Cpp-Unit-I/
│
├── 01_basic_data_types.cpp
├── 02_if_else.cpp
├── 03_loop_and_array.cpp
├── 04_functions.cpp
├── 05_class_and_object.cpp
├── 06_constructor_and_destructor.cpp
├── 07_static_member.cpp
└── 08_inline_and_friend_function.cpp

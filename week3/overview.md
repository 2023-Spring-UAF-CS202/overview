# Week 3

* Review of object-oriented programming from CS 201

* Students created their own custom data structure based on a problem that they came up with

* Sample code for a Hot Air Balloon data structure was provided

* Code for a class was broken into two files
  - a .h file that declares the class, but does not implement the body of the member functions
  - a .cpp file that implements the bodies of the member functions of the class

* That code was then used in a separate main function in another file
  - using #include "a_local_file.h"
  
* Misc
  - #pragma once
  - #include 
  - using
  - why *not* to use using in a header (polluting the namespace)
  - use of *class* keyword to declare a custom data type
  
* Constructors
  - default constructor
  - non-default constructor
  
Example: given either of these two, you should be able to provide the other
```
Spaceship(string name);
```
```
Spaceship enterprise{"NCC1701"};
```
  
* Member functions and member variables
  - what is a member function
  - what is a member variable
    * each object has its own copy of each member variable
  - use dot syntax to access member functions
  - public vs private

  
  
  
  

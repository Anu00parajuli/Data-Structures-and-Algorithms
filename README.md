# Data-Structures-and-Algorithms
## Chapter 1 
          **Introduction to Data Structure and Algorithm**

Data structure is a programming construction for representing of managing collection of data. It is a method of storing data for the purpose of efficient computation. It provides an organizational scheme 
that shows the relationship among the individuals elements and faciliates efficient data manipulations.
Data structure mainly specifies the organization of data and accessing methods. The study of data structure involves two goals :
 i) To identify and develop useful mathematical entities and operation and to determine what classes of problem can be solved by using the entities and operations.
 ii) To determine representation for those abstract entites and operations.
         Review of Array, Structure , Union , Class, Pointer:

 ## Arrays :
       Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value. To declare an array, define the variable type, specify the name of the array
followed.
         string cars[4];
         string cars ={"Volvo", "BMW","Ford","Mazda"};

## Pointer:
 We know that we can get the memory address of a variable by using '&' operator. A pointer variable points to a data type (for eg int, string, float) of the same type and is created with '*'
operator.
          string food="Pizza";
          string *ptr= &food;

## Class :
A class is a user defined datatype that works as an object constructor or as a "blueprint" for creating objects. A class is a collection of namefields and methods that apply to objects of that class type.Additionally
the C++ language implements the concept of information hiding, restricting access to certain members of the class to methods of the class itself.
To create a class, we use the 'class' keyword :
   class Myclass{
    public: //accessSpecifier
     int myNum;
     String myString;
};

## Structure:
Structure is a user defined data type in C language which allows us to combine data of different types together. Structure helps to construct a complex data type. It is somewhat similar to
an array,but array stores similar data types whereas structure stores different data types. To define a structure , we use 'struct' keyword.
     struct student{
        char first[10]; //memberOfTheStructure
        int roll;   //memberOfTheStructure   
}sname; //variableOfTheStructure

## Union :
Like structure, Union in c language is a user-defined data type that is used to store the different type of elements.
At once, only one member of the union can occupy the memory. In other words, we can say that the size of the union in any instance is equal to the size of its largest element.
   To define a union, we use 'union' keyword
     union Student{
       int roll; //size 2 byte
       char y;// size 1 byte
      }sname; //size=2 byte


## Abstract Data Types:
Abstract Data type (ADT) is a type (or class) for objects whose behaviour is defined by a set of value and a set of operations.
The definition of ADT only mentions what operations are to be performed but not how these operations will be implemented. It does not specify how data will be organized in memory and what 
algorithms will be used for implementing the operations. It is called “abstract” because it gives an implementation-independent view. The process of providing only the essentials and hiding
the details is known as abstraction.



    

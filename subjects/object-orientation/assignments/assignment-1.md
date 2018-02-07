# Object Orientation - Assignment 1

After having completed this assignment, you should be able to:
 - write, compile and execute a Java program
 - define classes with attributes and methods
 - distinguish static and dynamic methods
 - define objects as instances of such a class
 - use Java arrays
 - use rudimentary Java input/output
 - define and use a `toString()` method for user-defined classes
 - concentrate all input/output in a single class

To achieve the goals of this assignment you have to design and implement a Java program that
creates a group of students and offers the user the possibility to change the name of these students. Each student has a first name and a second name, both strings, and an integer for student
number. These values are specified upon the construction of the student object. The student
number is fixed, but the name can be changed by an appropriate setter method. The student
with name Alice Liddells and number 42 should be shown as Alice Liddells, s42.


The behavior of the program to create and manipulate a group of students is summarized as:

 1. Your program should ask the user how big the group of students is supposed to be and create a new group of the given size. 
 2. For each group member, your program should request a name and a student number and
add this student to the group until it is full.
 3. Afterwards the program should display the text The group now contains: and print all the students from the group.
 4. In a loop, the program will then ask the user to input the student number (only the numerical
part without the s ) alongside with a new name: Student number and new first/second name? Every time a name is changed, the entire group should be shown again on screen with the message The group now contains:.
5. The program terminates as soon as the user enters a negative student index.



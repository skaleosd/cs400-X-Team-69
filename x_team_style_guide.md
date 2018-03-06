# X-Team 69 Style Guide

In order for anyone, from a novice programmer to an expert programmer, to read and understand code, it is important to make sure that it follows this style guide. It consists of naming conventions and commenting styles for public and private members of a class or interface.

## Naming conventions
Use different version of CamelCase as a good practice when naming methods, variables, classes, etc to help them stand out to anyone who reads your code.

### Examples
* interfaces: should always be capitalized
`Interface Bicycle`
   
* classes: should be nouns and in mixed case by having the first letter of each inner word capitalized
`Class MotorBike`
    
* exception types: should be written in UpperCamelCase and must end with word "Exception" 
`ArithmeticException`
`IndexOutOfBoundsException`
`FileNotFoundException`
     
* fields: should have the following in order: Access modifier(public, private, protected, package), data type (ex: int), static or final (optional), type name
```
public class Person {
 private String address;
 protected int speed;
 public int height;
}
```
* methods: should be written in lowerCamelCase and should be verbs
```
run() 
walkFast()
getScore()
```

* parameters: camel case, as short of name as possible while able to understand purpose
 ```
 public static void int multiply (int x, int y)  {// x and y are parameters
     return (x*y);
 ```
* local variables: 
  1. Should be short (more than one character, unless it's a temporary variable) 
  2. Should never start with special characters, including an underscore or a $ sign
  3. Should be easy to understand like an acronym
  ```
  int size = 0;
  int time = 1;
  ```
  
* instance constants: Should just have data type followed by type name
 ```
 public class Human {
    int a;
    Person p;
 ```
 
* class constants: Should include static final and followed by data type and type name must be all uppercase
 ```
 public class Car {
   static final int MILES_PER_HOUR = 20;
  ```

## Commenting style for public and private members of a class or interface:

Comment for every method and class, describing the objective for the method annd class. Also describe the return value for the method.
We should have the in-line comment to explain the code we use.

### Examples

* classes
```
/////////////////////////////////////////////////////////////////////////////
//Semester:         CS400 Spring 2018
//PROJECT:          (project name)
//FILES:            (filename)
//                  
//                  
//
//USER:             (author name)
//
//Instructor:       Deb Deppeler (deppeler@cs.wisc.edu)
//Bugs:             (known bugs)
//Info:			          (additional information)
//Due Date:		       (due date)
//
////////////////////////////////////////////////////////////////////////////
```
* fields
```
@param group  group number................
```
* constructors
```
/**
* Constructor usage........
* @param group  group number...........
*/
```
* methods
```
/**
 * method usage.............. 
 * ..........
 *
 * @param group  group number...........
 *
 */
```
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  ```
      if(boolean statement){
          code
      }
  ```
  * switch statement
  ```
      switch (choice) {
                case 1:  code
                         break;
                case 2:  code
                         break;
                case 3:  code
                         break;
      }
  ```
  * while loops
  ```
      while(boolean statement){
          code
      }
  ```
  * for loops
  ```
      for (int i = 0; i < 100; i++){
          code
      }
  ```
  * enhanced for loops
  ```
      for (String group : array) {
        System.out.println("Group: " + group);
      }
  ```

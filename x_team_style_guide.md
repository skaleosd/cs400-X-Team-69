# X-Team 69 Style Guide

<brief description of your team's opinion or philosophy regarding Style Guides>

## Naming conventions

<brief statement describing your team's naming conventions>

### Examples
* interfaces
* classes
* exception types
* fields
* methods camel case (yourMethodsShouldLookLikeThis)
* parameters camel case, as short of name as possible while able to understand purpose
* local variables 
* instance constants
* class constants

## Commenting style for public and private members of a class or interface:

comment for every method and class, describing the objective for the method annd class. Also describe the return value for the method.
We should have the in-line comment to explain the code we use.

### Examples

* classes
```
/////////////////////////////////////////////////////////////////////////////
//Semester:         CS400 Spring 2018
//PROJECT:          (project name)
//FILES:            filename
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

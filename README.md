```bash
  intro c++
```

# Wednesday 26th Lecture
  
## printing a simple hello

  ```Ruby
#include <iostream> 
//header file library that lets us work with input and output objects

using namespace std; 
//means that we can use names for objects and variables from the standard library

int main() {
  cout << "Hello World!";
  return 0;
}
```
  
## c++ has 3 data types
  - primative types - like double, int, bool, char, string
  
  - classes - to create a class use the 'class' keyword
  ```Ruby
  class MyClass {      // The class
  public:             // Access specifier
    int myNum;        // Attribute (int variable)
    string myString;  // Attribute (string variable)
  };
  ```
  
  - pointers - variable that points to a data type (variable that stores the memory address as its value)
  
## identifiers 
  - in c++, indentifiers can be of any legth
  - must start with a letter or an underscore
  - they are case sensitive
  
![image](https://user-images.githubusercontent.com/88512549/151238273-471bd7a3-b9da-430b-9d0f-791629f68fe3.png)

## logical operators and special characters

![image](https://user-images.githubusercontent.com/88512549/151239732-9cf65d47-45ab-400a-a5af-e524e6be1144.png)

![image](https://user-images.githubusercontent.com/88512549/151239766-4d16ed59-be24-48cb-92a3-07f67ac2eef9.png)


we can decalre many variables at a time

![image](https://user-images.githubusercontent.com/88512549/151240132-5631debc-91a5-4e77-8737-cf6677dc5616.png)


## fuctions (similar to methods in java)
### A function is a block of code which only runs when it is called, you can pass data (parameters) into the function

- the function can return a value
- the word return causes an immediate jump out of the method

### declaring a function requires:
- the return type, the name of the function, and parameters (if any)
- the body of the function (code to be executed)

example: 

![image](https://user-images.githubusercontent.com/88512549/151240983-2bb7027d-d666-4a7d-94b9-d94411d5100c.png)

## pass by copy
passing by copy only passes the value of the variable not the reference, therefore the variable does not get changed in this example below; 

![image](https://user-images.githubusercontent.com/88512549/151242472-d7721539-ef4b-4986-8a2d-bab5056d872c.png)

output: 

![image](https://user-images.githubusercontent.com/88512549/151243333-f46477e3-d870-49ff-b4f9-69bbc123c853.png)


## pass by reference
passing by the reference does change its value of the argument
### using the character '&' before the argument variable, will send the reference affecting the value of the argument if modified in the function

![image](https://user-images.githubusercontent.com/88512549/151243281-ddb69d65-64e8-4697-8645-25d12975667d.png)

output:

![image](https://user-images.githubusercontent.com/88512549/151260782-194ffa0c-a78f-4242-bca1-2d6949b04f5f.png)

x has now been changed by the function

## function prototypes
  - Function prototyping is one very useful feature of C++ function. 
  - A function prototype describes the function interface to the compiler by giving details such as the number and type of arguments and the type of return values.

### essentially, tell the program that there will be some functions later on 
example: 

![image](https://user-images.githubusercontent.com/88512549/151244050-005bba30-f31e-40a0-a3d2-808b02c4e05b.png)








# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Employee with method display(). Inside display(), return the current object using this. Create another method that calls display().printName()

## AIM:
To create an Employee class where the display() method returns the current object using this, and demonstrate calling display().printName() from another method.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Write a method display() that returns the current object using return this;.

Write a method printName() to print the employee name.

Add another method show() that internally calls display().printName().

In the main() method, read the employee name from the user.

7.Create an Employee object and set the name.

Call both display().printName() and show() to demonstrate method chaining.





## PROGRAM:
 ```java
/*
Program to implement a Access Modifiers using Java
Developed by: JAI HARISH R
RegisterNumber: 212224040124
*/

import java.util.Scanner;

class Employee {
    String name;

    void setName(String name) {
        this.name = name;  
    }

    Employee display() {
        return this;  
    }

    void printName() {
        System.out.println("Employee Name: " + name);
    }
}

class prog {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String inputName = scanner.nextLine();

        Employee emp = new Employee();
        emp.setName(inputName);
        emp.display().printName();  
    }
}
```




## OUTPUT:
<img width="777" height="375" alt="image" src="https://github.com/user-attachments/assets/4a98e8df-e867-4c53-a976-d7ddb30a578f" />



## RESULT:

Therefore the program successfully returns the current object using this inside the display() method.

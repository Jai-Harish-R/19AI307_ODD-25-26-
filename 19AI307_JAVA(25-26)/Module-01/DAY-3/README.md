# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Display Factors of a Number

## AIM:
To write a Java program that reads an integer from the user and displays all the factors of the given number.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	If yes, print i as a factor.

4.Continue the loop until all factors are printed.

5.End the program.





## PROGRAM:
 ```JAVA
/*
Program to implement a Looping Statement using Java
Developed by: JAI HARISH R
RegisterNumber: 212224040124
*/

## SOURCE CODE:

import java.util.Scanner;

public class Factors {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();

        System.out.print("Factors: ");
        for (int i = 1; i <= n; i++) {
            if (n % i == 0) { 
                System.out.print(i + " ");
            }
        }
    }
}


```


## OUTPUT:



## RESULT:
Therefore, the program successfully reads a number from the user and computes its factors.

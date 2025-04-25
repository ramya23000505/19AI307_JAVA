# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To write a Java program that takes three numbers from the user and prints the greatest of the three numbers.

## ALGORITHM :
1.Start the program.

Import the necessary package java.util.Scanner for taking input from the user.

Define a class named GreatestNumber.

Implement the main() method as the entry point of the program.

Create an instance of the Scanner class named sc to read user input.

Read three numbers num1, num2, and num3 from the user using sc.nextInt().

Compare the three numbers to find the greatest number using conditional statements (if, else if, else).

Print the greatest number.

End the program.


## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: RAMYA R
RegisterNumber:  21222320169
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Demo {

    
  public static void main(String[] args)
    {
        Scanner in = new Scanner(System.in);

        int num1=in.nextInt();
        int num2=in.nextInt();
        int num3=in.nextInt();
        
        if((num1>num2) &&(num1>num3))
        {
        	System.out.println(num1+" is the Greatest value");
        }
        else if((num2>num1) &&(num2>num3))
        {
        	System.out.println(num2+" is the Greatest value");
        }
        else
        {
        	System.out.println(num3+" is the Greatest value");
        }
    }
}
```



## OUTPUT:
![image](https://github.com/user-attachments/assets/66356188-2289-4018-9563-dd43ef448c31)



## RESULT:
Thus, the program successfully takes three numbers from the user and prints the greatest of the three numbers.




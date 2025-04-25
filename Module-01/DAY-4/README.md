# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To write a Java program that calculates the area of a trapezium using an instance method calculateArea() and returns the area as a double.

## ALGORITHM :
1.	Start the program.
2. Define a class named Area.
3. Define an instance method calculateArea() with double return type to calculate the area of the trapezium.
4. Declare local variables for height h, base1 b1, and base2 b2.
5. Initialize the values for h, b1, and b2 as per the user's input or preset values.
6. Calculate the area using the formula: Area = (1/2) * h * (b1 + b2).
7. Return the calculated area from the method.
8. In the main method, create an object of the Area class.
9. Call the calculateArea() method using the created object and print the result.
10. End

## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: RAMYA R
RegisterNumber:  212223230139
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Area {
       public double calculateArea() 
       {
          Scanner sc = new Scanner(System.in);
          double b1 = sc.nextDouble();
          double b2 = sc.nextDouble();
          double h = sc.nextDouble();
              
          double area = 0.5 * h * (b1 + b2);
      
          return area;
      }
       public static void main(String[] args) {
       Area obj=new Area();
       double area=obj.calculateArea();
       System.out.println("Area of Trapezium is "+area);
    }
}

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/4a45e442-6a74-41c2-86de-5c27e78f09c7)



## RESULT:
Thus, the Java program to print area of rectangle by defining instance method and local variable value as 10,20 was created successfully.


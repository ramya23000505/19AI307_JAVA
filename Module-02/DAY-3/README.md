# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a java program to read 3 values in array and display the array elements using single dimensional array and standard method.

## ALGORITHM :
1.	Start the program.
2.	Define a class 'ArrayExample'
3.	Create a method displayArray(int[] arr)
4.	Print the message "One dimensional array elements are"
5.	Loop through the array using a for loop and print each element of the array.
6.	In the main method: Create a Scanner object to read input from the user.
7.	Declare a one-dimensional integer array arr of size 3
8.	Use a for loop to take 3 integer inputs from the user and store them in the array arr
9.	Call the displayArray method and pass the array arr to it for displaying the array elements
10.	End the program.


## PROGRAM:
```
Program to implement a Single Array using Java
Developed by: RAMYA R
RegisterNumber: 212223230169
```

## Sourcecode.java:

```
import java.util.Scanner;
public class ArrayExample 
{
    public static void displayArray(int[] arr) 
    {
        System.out.println("One dimensional array elements are");
        for
        for (int i = 0; i < arr.length; i++) 
        {
            arr[i] = scanner.nextInt();
        }

        displayArray(arr);
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/963f15a7-7a36-4c58-9400-ddcbb1c1dbc7)


## RESULT:
Thus, the java program to read 3 values in array and display the array elements using single dimensional array and standard method was executed successfully.

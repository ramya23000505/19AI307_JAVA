# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program to find the sum of all the elements present in a 2-D array.

## ALGORITHM :
1.	Start the program.
2.	Define a class 'Demo'
3.	In the main method: Declare a 2D array a with predefined values.
4.	Initialize a variable sum to 0, which will be used to store the sum of array elements.
5.	Use nested loops to iterate through the 2D array:
   Outer loop: Iterate over the rows of the 2D array (3 rows)
  	Inner loop: Iterate over the columns of each row (5 columns)
  	Add each element of the array to sum
6. Print the value of sum which represents the sum of all elements in the 2D arra
7. End the program.


## PROGRAM:
```
Program to implement a Multi Dimensional Array using Java
Developed by: RAMYA R
RegisterNumber: 212223230169
```

## Sourcecode.java:

```
import java.util.*;
public class Demo
{
    public static void main(String args[])
    {
        int a[][]={{1,2,3,4,5},{2,4,6,8,10},{1,3,5,7,9}};
        int sum=0;
        for(int i=0;i<3;i++)
        {
            for(int j=0;j<5;j++)
            sum=sum+a[i][j];
        }
        System.out.println("Sum of all elements is: "+sum);
        
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/c276aa9c-3031-4130-a03d-9cbca900fd76)


## RESULT:
Thus, the java program find the sum of all the elements present in a 2-D array was executed successfully.

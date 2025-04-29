# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable small with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with small. If an element is smaller, update small.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
```
Program to implement a Smallest Element in an Array
Developed by: RAMYA R
RegisterNumber: 212223230169
```

## Sourcecode.java:

```
import java.util.*;
public class Demo
{
    public static void main(String agrs[])
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int a[]=new int[n];
        for(int i=0;i<n;i++)
        a[i]=sc.nextInt();
        int small=a[0];
        for(int i=0;i<n;i++)
        {
            if(a[i]<small)
            small=a[i];
        }
        System.out.println("Smallest Number = "+small);
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/b6d7dda7-5b29-4ce1-9644-efa1d7021107)


## RESULT:
Thus, the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.

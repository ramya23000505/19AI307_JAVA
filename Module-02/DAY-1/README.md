# Ex.No:2(A)  STATIC METHOD

## AIM:
To create a java program for SumOfDigits using static and method.

## ALGORITHM :
1.  Start the program.
2.  Import the "Scanner" class to get input from the user
3.  Define a class "SumOfDigits"
4.  Define a static method sumOfDigits(int number)
5.  Initialize an integer variable sum to 0
6.  While the number is not equal to 0: Add the last digit of the number to sum using number % 10, Remove the last digit by dividing the number by 10 (number /= 10)
7.  Return the value of sum
8.  Create a Scanner object to take input from the user in the 'main'
9.  Read the input number using scanner.nextInt()
10.  Call the static method sumOfDigits(inputNumber) and print the result
11.	End the program.


## PROGRAM:
```
Program to implement a Static method using Java
Developed by: RAMYA R
RegisterNumber: 212223230169
```

## Sourcecode.java:

```
import java.util.Scanner;
public class SumOfDigits 
{
    public static int sumOfDigits(int number) 
    {
        int sum = 0;
        while (number != 0) 
        {
            sum += number % 10;
            number /= 10;
        }
        return sum;
    }
    public static void main(String[] args) 
    {
        Scanner scanner = new Scanner(System.in);
        int inputNumber = scanner.nextInt();
        int result = sumOfDigits(inputNumber);
        System.out.println("Sum of digits of the number " + inputNumber + " is: " + result);
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/f9584a13-99ae-4dea-8ebe-32c904cb3695)


## RESULT:

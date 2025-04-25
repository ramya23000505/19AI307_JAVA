# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program that takes a number from the user (between 1 and 7) and displays the corresponding name of the weekday.

## ALGORITHM :
1.	Start the program.

2. Import the necessary package java.util.Scanner to read user input.

3. Define a class named Weekday.

4. Implement the main() method as the entry point of the program.

5. Create an instance of the Scanner class named sc to read user input.

6. Prompt the user to enter an integer between 1 and 7 using System.out.print().

7. Read the input number using sc.nextInt().

8. Use a switch-case statement to match the number and print the corresponding weekday.

9. End the program.



## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: RAMYA R
RegisterNumber:  212223230169
*/
```

## Sourcecode.java:

```
import java.util.*;
public class vowel
{
    public static void main(String argv[])
    {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        switch(n)
        {
            case 1: System.out.println("Monday"); break;
            case 2: System.out.println("Tuesday"); break;
            case 3: System.out.println("Wednesday"); break;
            case 4: System.out.println("Thursday"); break;
            case 5: System.out.println("Friday"); break;
            case 6: System.out.println("Saturday"); break;
            case 7: System.out.println("Sunday"); break;
            default: System.out.println("Invalid day range"); break;
            
        }
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/d120539f-bc6b-489b-922a-e837d1edb23a)



## RESULT:
Thus, the program successfully takes a number from the user and prints the corresponding name of the weekday.

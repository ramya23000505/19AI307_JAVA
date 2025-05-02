# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program to use reverse() method of the StringBuilder class reverses the current String.

## ALGORITHM :
1.	Start the program.
2.	Import necessary libraries (java.util.*).
3. Create a Scanner object to take user input.
4. Read the input string from the user.
5. Create a StringBuilder object and initialize it with the input string.
6. Call the reverse() method on the StringBuilder object.
7. Print the reversed string using System.out.println().
8. End the program.


## PROGRAM:
```
Program to implement a String Buffer using Java
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
        String str=sc.next();
        int l=str.length();
        for(int i=l-1;i>=0;i--)
        System.out.print(str.charAt(i));
    }
}
```


## OUTPUT:

|  Input  |  Expected  |   Got   |
|---------|------------|---------|
| welcome |  emoclew   | emoclew |
| bag     |  gab       | gab     |
| tree    |  eert      | eert    |



## RESULT:
Thus the java program to use reverse() method of the StringBuilder class reverses the current string was executed successfully.

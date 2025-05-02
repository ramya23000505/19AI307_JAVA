# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program to read input, split word from sentence and use string builder.

## ALGORITHM :
1.	Start the program.
2.	Import necessary classes:
   Import Scanner for reading input.
  	Import StringBuilder for manipulating the string.
3. In the main method:
   a) Create a Scanner object sc to read input from the user.
   b) Read the entire input sentence using sc.nextLine() and store it in a string variable str.
4. Create a StringBuilder object sb.
5. Split the sentence into words using split() method.
6. Print each word from the array:
   Use a for-each loop to iterate over the array s.
   Print each word in the array using System.out.println(a).
7. End the program.


## PROGRAM:
```
Program to implement a StringBuilder Object Reference in Java
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
        String str=sc.nextLine();
        StringBuilder sb=new StringBuilder(str);
        String s[]=str.split("\\s+");
        for(String a:s)
        System.out.println(a);
    }
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/df037656-fc0a-4826-be3b-01146f88e734)


## RESULT:
Thus the Java program successfully reads input, split word from sentence and use string builder.

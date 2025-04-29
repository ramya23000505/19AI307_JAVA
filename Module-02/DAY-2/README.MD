# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To develop a Java Program to display "welcome to java" using modifiers only.

## ALGORITHM :
1.	Start the program.
2.	Define a class 'A'
3. Inside class A, create a public method display() : This method will print the message "Welcome to Java" when called.
4. In the main method: Create an object obj of class A
                       Call the display() method using the object obj to print the message "Welcome to Java"
5. End the program.


## PROGRAM:
```
Program to implement a access modifiers using Java
Developed by: RAMYA R
RegisterNumber: 212223230169
```

## Sourcecode.java:

```
public class A 
{ 
public void display() 
    { 
        System.out.println("welcome to java"); 
    } 

    public static void main(String args[])
    {
        A obj = new A();
        obj.display();
    }
}
```


## OUTPUT:
 
|    Expected    |        Got      |
|----------------|-----------------|
|welcome to java | welcome to java |


## RESULT:
Thus the java program to display "welcome to java" using modifiers only was executed successfully.




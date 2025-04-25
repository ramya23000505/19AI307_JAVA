# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program in a class named Demo that divides 3210 by 3, finds the modulus of the quotient with 6, multiplies the result by 10, and displays the final value.

## ALGORITHM :
1. Start the program.

2. Declare an integer variable number and initialize it to 3210.

3. Declare an integer variable quotient to store the result of dividing number by 3.

4. Calculate the quotient by dividing 3210 by 3 and store it in quotient.

5. Declare an integer variable modResult to store the result of the modulus operation (quotient % 6).

6. Calculate the modulus of quotient by 6 and store the result in modResult.

7. Declare an integer variable finalResult to store the result of multiplying modResult by 10.

8. Calculate the final result by multiplying modResult by 10 and store it in finalResult.

9. Print the finalResult using the System.out.println() method.

10.End the program.





## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: RAMYA R
RegisterNumber:  212223230169
*/
```

## Sourcecode.java:
```
public class Demo{
    public static void main(String argv[])
    {
        int num = 3210;
        int quo = num/3;
        int mod = quo%6;
        int res = mod*10;
        System.out.println(res);
    }
}
```


## OUTPUT:
|-----------|-----|
| EXCEPCTED | GOT |
|-----------|-----|
|     20    |  20 |
|-----------|-----|
## RESULT:
Thus, the program successfully divided 3210 by 3, took modulus of the quotient with 6, multiplied the result by 10, and displayed the final result using the class named 'Demo'.

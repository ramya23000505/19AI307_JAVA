# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named Distance that adds two distances (in feet and inches) using a third object and displays the result.

## ALGORITHM :
1. Define the Class
 
Create a public class named Distance.

3. Declare Variables
 
Inside the class, declare double variables: feet, inches, sum1, and sum2 to store input and results.

5. Create Objects

In the main method, create three Distance objects: obj1, obj2, and obj3.

7. Assign Values
   
Assign 20.5 feet and 5.2 inches to obj1; assign 13.5 feet and 3.2 inches to obj2.

9. Add Feet Values
    
Add obj1.feet and obj2.feet and store the result in obj3.sum1.

11. Add Inches Values
    
Add obj1.inches and obj2.inches and store the result in obj3.sum2.

13. Display the Result
    
Print the total distance in the format: “Total Distance is X feet and Y inches”.

14. End Program
    
The program ends after output is displayed.

## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: RAMYA R
RegisterNumber:  2122223230169
*/
```

## Sourcecode.java:
```
public class Distance
{
    double feet,inches,sum1,sum2;
    public static void main(String[] args)
    {
        Distance obj1=new  Distance();
        Distance obj2=new  Distance();
        Distance obj3=new  Distance();

        obj1.feet=20.5;
        obj1.inches=5.2;
        obj2.feet=13.5;
        obj2.inches=3.2;
        
        obj3.sum1 = obj1.feet+ obj2.feet;
        obj3.sum2 = obj1.inches+ obj2.inches;
      
        System.out.println("Total Distance is "+obj3.sum1+" feet and "+obj3.sum2+" inches");
    }
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/4a559a9d-19c7-4cd2-991b-80308acd671b)

## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.

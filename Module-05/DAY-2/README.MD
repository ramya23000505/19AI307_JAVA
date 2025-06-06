# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Define `Cylinder` class:
-	a) Private variables `radius` and `height`
-	b) `setRadius(int r)` and `setHeight(int h)` methods to set values
-	c) `getVolume()` method:
- i) Calculate and print `volume = pi * radius * radius * height`
3.	In `Main` class `main` method:
-	a) Use `Scanner` to read `radius` and `height`
-	b) Create `Cylinder` object, set values, and call `getVolume()`
4.	End



## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by:RAMYA R
RegisterNumber: 212223230169
*/
```

## Sourcecode.java:
```java
import java.util.*;

class Num {
    private int r, h;
    
    
    public void setValues(int r, int h) {
        this.r = r;
        this.h = h;
    }
    
    public double calculateVolume() {
        return (22.0 / 7)  * r * r * h;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        int r = sc.nextInt();
        int h = sc.nextInt();
        
        Num obj = new Num();
        obj.setValues(r, h);
        System.out.println("volume of Cylinder is: " + obj.calculateVolume());
        
    }
}
```
## OUTPUT:

![image](https://github.com/akshayaamanagal/19AI307_JAVA/blob/57a9eed3754de7da917e6ae395448054154907eb/Module-05/DAY-2/image.png)


## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.




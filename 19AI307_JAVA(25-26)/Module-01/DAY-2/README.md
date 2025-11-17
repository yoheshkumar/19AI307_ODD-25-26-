# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
In a magical building, an elevator behaves oddly: If the floor number is divisible by 3 and 5, it says "Skipped". If the floor number is divisible by 3 only, it says "Beware!". If the floor number is divisible by 5 only, it says "Blessings!". Otherwise, it announces the floor number - print - "Floor {number}" . Write a Java program to simulate this elevator logic for a given floor number.

## AIM:
To write a Java program that demonstrates the use of conditional statements (if, else if, else) to simulate the logic of the magical elevator based on a user-provided floor number.

## ALGORITHM :
```
1.Start the program and import the java.util.Scanner package.
2.Inside the main method, create a Scanner object, prompt the user for a floor number, and read the integer value into a variable floorNumber.
3.Implement the logic using an if-else if-else chain:
4.First, check if floorNumber is divisible by both 3 AND 5. If true, print "Skipped".
5.Else, check if floorNumber is divisible by 3. If true, print "Beware!".
6.Else, check if floorNumber is divisible by 5. If true, print "Blessings!".
7.Else (if none of the above are true), print "Floor " + floorNumber.
8.Close the Scanner object to prevent resource leaks.
9.End the program.
```
## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: YOHESH KUMAR R.M
RegisterNumber:  212222240118
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class Java{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        if(n%3==0 && n%5==0){
            System.out.println("Skipped");
        }else if(n%3==0){
            System.out.println("Beware!");
        }else if(n%5==0){
            System.out.println("Blessings!");
        }else{
            System.out.println("Floor "+n);
        }
    }
}

```



## OUTPUT:



## RESULT:
Thus, the Java program to implement conditional statements for the magical elevator logic was successfully compiled and executed, providing the correct output for various inputs.


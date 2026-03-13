# Ex.No:1(D) ARRAYS

## QUESTION:

Write a Java program to sort an array in ascending order.


| Input | Result |
|-------|--------|
| 5<br>5<br>3<br>8<br>6<br>2 | 2 3 5 6 8 |

## AIM:
To write a Java program that reads an array of integers and sorts the elements in ascending order using built-in array methods.

## ALGORITHM :
1.  Start the program.
2.  Import the required package java.util.
3.  Read the size of the array from the user.
4.  Declare an integer array with the given size.
5.  Read each array element using a loop.
6.  Use Arrays.sort() to sort the array in ascending order.
7.  Print the sorted array elements.
8.  End the program.

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: SANJEV R M
RegisterNumber: 212223040186
*/
```

## SOURCE CODE:
```java
import java.util.*;
class prog{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int a[]=new int[n];
        for (int i=0;i<n;i++)
        {
            int x=sc.nextInt();
            a[i]=x;
        }
        Arrays.sort(a);
        for (int i=0;i<n;i++)
        {
            System.out.print(a[i]+ " ");
        }
    }
}
```

## OUTPUT:
<img width="500" height="694" alt="image" src="https://github.com/user-attachments/assets/c6ce8939-5d9c-4ef0-af37-f4b8df55f867" />

## RESULT:
Thus, the Java program to sort an array in ascending order was executed successfully.










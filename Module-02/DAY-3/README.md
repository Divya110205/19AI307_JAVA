# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a Java program to read 3 values and display all 3 values from an array using a single-dimensional array and standard method.

## ALGORITHM :
1.	Start the program.
2.	Import the Scanner class from the java.util package.
3.	Define a class named ArrayExample.
4.	Inside the main method:
i)Create a Scanner object called scanner to take user input.

ii)Declare an integer array values of size 3.

iii)Use a for loop to iterate from i = 0 to i < 3:

iv)Take input from the user and store it in values[i].
5.Define a standard method displayArray(int[] array):
6.Use a for loop to iterate through the array.
7.Print each element followed by a space.
8.Call the displayArray method from the main method.
9.Close the scanner to release resources.
10.End the program.

## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: Divya.A 
RegisterNumber: 212222230034
*/
```

## Sourcecode.java:

```
import java.util.*;
public class OnedimensionalStandard
{
	public static void main(String args[])
	{ 
	Scanner sc= new Scanner(System.in); 
	int[] a=new int[3];  
	for(int i=0;i<3;i++)
	{
	    a[i]=sc.nextInt();
	}
	 
	 
	System.out.println("One dimensional array elements are");    
	for(int i=0;i<3;i++)
	{
	   System.out.println(a[i]);
	}
	 

	}
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/0c4c72c4-c216-4774-aaeb-0da526924e7f)


## RESULT:
Thus, the Java program to read 3 values and display all 3 values from an array using a single-dimensional array and a standard method was executed successfully.





# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print Employee details (name, department, age), where department and age are the same for all employees. Use static variables to represent department and age and demonstrate their use in accessing shared values across all class objects.

## ALGORITHM :
1.Start the program.

2.Create a class named Employee.

3.Declare static variables dept and age in the Employee class.

4.Declare an instance variable name.

5.Create a constructor to initialize the employee's name.

6.Define a method displayDetails() to print the employee's name, department, and age.

7.In the main method of another class:

i)Assign values to the static variables dept and age.

ii)Create multiple Employee objects with different names.

iii)Call the displayDetails() method for each employee.

8.End the program.

## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: Divya.A
RegisterNumber: 212222230034 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    static String dept="AIDS";
    static int age=18; 
    public static void main(String[] args){
        Scanner input=new Scanner(System.in);
        String name1,name2;
        name1=input.nextLine();
        name2=input.nextLine();
        System.out.println("Student name: "+name1+" Department: "+dept+" Age: "+age);
        System.out.print("Student name: "+name2+" Department: "+dept+" Age: "+age);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/f5b58b3c-f6c1-420b-bc83-406970b30a71)


## RESULT:
Thus, the Java program for the concept of using static variables for shared data (department and age) was correctly implemented and verified successfully.


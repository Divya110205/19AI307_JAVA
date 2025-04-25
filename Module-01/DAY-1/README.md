# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with a String variable 'dept', String variable 'name', integer variable 'rollno', and double variable 'marks'.

## ALGORITHM :

1.Start the program.

2.Define a class named 'Student'.

3.Declare the following variables inside the class:

            - String name and initialize with "John".

            - String dept and initialize with "Computer Science".

            - int rollno and initialize with 101.

            -double marks and initialize with 87.5.

4.Define another class named 'Test'.

5.Inside the main method of the Test class:

6.Create an object obj of the Student class.

7.Print the values of name, dept, rollno, and marks using the object.

8.End the program.





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Divya.A
RegisterNumber:  212222230034
*/
```

## Sourcecode.java:
```
class Student{
    String dept;
    String name;
    int rollno;
    double marks;
}
public class Main {
    public static void main(String[] args) {
        Student obj= new Student();
        obj.dept="AIML";
        obj.name="John";
        obj.rollno=15;
        obj.marks=89.95;   
        System.out.println(obj.dept+" "+obj.name+" "+obj.rollno+" "+obj.marks);
    }   
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/25e4c4a6-e3be-4737-b058-93eac737be7a)


## RESULT:
Thus, the class named 'Student' with variables dept, name, rollno, and marks was created and accessed successfully using an object.

# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To write a Java program to demonstrate the use of transient keyword in serializing employee details (name, designation, id) using the Serializable interface. The id field should be declared as transient to prevent it from being serialized.

## ALGORITHM :
1.	Define a class Employeeinfo that implements Serializable.
2.	Declare name and designation as regular fields and id as a transient field.
3.	Get employee details (name, designation, id) as input from the user
4.	Serialize the Employeeinfo object and write it to emp.txt.
5.	Deserialize the object from emp.txt.
6.	Print the employee details. The id should appear as 0 (default value) because it is transient.
7.	Delete the emp.txt file.
8.	Try to read from the deleted file to demonstrate file handling with exceptions

## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: Divya.A
RegisterNumber: 212222230034 
*/
```

## Sourcecode.java:
```python

class Employeeinfo implements Serializable
{
    String name;
    String desi;
    transient int id;
   
    Employeeinfo(String n, String r, int na)
    {
    this.name = n;
    this.desi = r;
    this.id=na;
   
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/c7f4f415-35d2-4c39-9797-8a26d54fc9f9)


## RESULT:
Thus, the Java program to demonstrate the use of the transient keyword in serializing employee details was implemented, executed, and verified successfully.


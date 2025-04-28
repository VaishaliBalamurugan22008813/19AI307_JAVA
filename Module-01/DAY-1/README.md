# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: VAISHALI BALAMURUGAN
RegisterNumber:  212222230164
*/
```

## Sourcecode.java:

```
import java.util.*;
class Student
{
    String name;
    String reg_no;
    String cge_name;
}
public class Main
{
    public static void main(String[] args)
    {
        Student obj=new Student();
        Scanner sc=new Scanner(System.in);
        obj.name=sc.next();
        obj.reg_no=sc.next();
        obj.cge_name=sc.next();
        System.out.println("Your Name is: "+obj.name);
        System.out.println("Your Registration number is: "+obj.reg_no);
        System.out.println("Your College Name is: "+obj.cge_name);
    }
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/327cc273-17fb-4f89-a7df-1084fc8bd7f9)


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.

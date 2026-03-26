# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to reverse a given string.

Input	Result
welcome
Reversed string: emoclew


## AIM:
To develop a Java program to reverse a given string.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the input string.
4. Convert the string into characters.
5. Traverse the string from last to first.
6. Build the reversed string.
7. Display the reversed string.
8. Stop the program.





## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: JESPIAH SHIHANA P S
RegisterNumber:  212223040077
*/
```

## SOURCE CODE:

```
import java.util.*;
class prog
{
    public static void main(String [] args)
    {
        Scanner sc=new Scanner(System.in);
        String str=sc.next();
        String rev="";
        for(int i=str.length()-1;i>=0;i--)
        {
            rev=rev+str.charAt(i);
        }
        System.out.print("Reversed string: "+rev);
    }
}
```





## OUTPUT:
<img width="733" height="259" alt="image" src="https://github.com/user-attachments/assets/d908776f-64b8-43d1-89ce-04e77568b178" />



## RESULT:
The program was executed successfully and the string was reversed correctly.

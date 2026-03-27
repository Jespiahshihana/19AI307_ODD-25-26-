# Ex.No:3(F) WRAPPER CLASS

## QUESTION:
Write a Java program to check if a number is an Armstrong number using Math.pow() and the Integer wrapper class. Take input from the user.

Input	Result
153
153 is an Armstrong number.

## AIM:
To develop a Java program using wrapper class and built-in methods to perform numerical computation.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read an integer input.
4. Convert number to string to count digits.
5. Extract each digit using wrapper methods.
6. Use Math.pow() to calculate powers.
7. Find sum of powered digits.
8. Compare with original number.
9. Display result.
10. Stop the program.





## PROGRAM:
 ```
/*
Program to implement a Wrapper Class using Java
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
        int n=sc.nextInt();
        int sum=0;
        int temp=n;
        int dig=Integer.toString(n).length();
        while(temp>0)
        {
            int d=temp%10;
            sum+=Math.pow(d,dig);
            temp=temp/10;
        }
        if(sum==n)
        {
            System.out.println(n+" is an Armstrong number.");
        }
        else
        {
            System.out.println(n+" is not an Armstrong number.");
        }
    }
}
```






## OUTPUT:

<img width="805" height="229" alt="image" src="https://github.com/user-attachments/assets/a6c647be-b060-4e98-9f7a-3921138449a8" />


## RESULT:
The program was executed successfully and checked whether the number is an Armstrong number.

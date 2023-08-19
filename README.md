# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Start

Create a class and declare two variable with string datatype

Loop over the entire string and reverse it

Use if condition to check whether the string and the reversed string is equal or not

print palindrome if it's equal else print not a palindrome.

stop
## Program:
```
Name: Varsha Ajith
Reg No: 212221230118
```
```
using System;
namespace palindrome
{
    class stringl
    {
        public static void Main(string[] args)
        {
            string str,rev="";
            int n;
            Console.WriteLine("Enter a String :");
            str=Console.ReadLine();
            n=str.Length - 1;
            for(int i=n;i>=0;i--)
            {
                rev=rev+str[i];
            }
            if(rev==str)

                Console.WriteLine("{0} is Palindrome",str);
            else
                Console.WriteLine("{0} is not Palindrome",str);

        }
    }
}
```
## Output:
<img width="960" alt="image" src="https://github.com/VarshaAjith1110/Palindrome/assets/94222288/8b6f1656-6377-4ec3-87cd-02145242b0f9">

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.

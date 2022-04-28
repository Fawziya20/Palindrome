# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:

Step1:
Start

Step2:
Create a class and declare two variable with string datatype

Step3:
Loop over the entire string and reverse it

Step4:
Use if condition to check whether the string and the reversed string is equal or not

Step5:
print palindrome if it's equal else print not a palindrome.

Step6:
stop

## Program:

```
using System;
namespace activity
{
    class Palindrome
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter the string: ");
            s = Console.ReadLine();
            s=s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i];
            }
            if (revs == s)
            {
                Console.WriteLine("The Entered String is Palindrome");
            }
            else
            {
                Console.WriteLine("The Entered String is not Palindrome");
            }
        }
    }
}
```

## Output:
![Program cs - c# project - Visual Studio Code 28-04-2022 21_03_51](https://user-images.githubusercontent.com/75235022/165789802-2ae9e69e-b321-4b5f-af40-d64ef0f1f135.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.

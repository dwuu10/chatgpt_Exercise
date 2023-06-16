write an if else statement in c#

ChatGPT
Certainly! Here's an example of an if-else statement in C#:

csharp
Copy code
int number = 10;

if (number > 0)
{
Console.WriteLine("The number is positive.");
}
else if (number < 0)
{
Console.WriteLine("The number is negative.");
}
else
{
Console.WriteLine("The number is zero.");
}

In this example, we have an integer variable named number with a value of 10. The if-else statement checks the value of number and executes the corresponding block of code based on the condition. If number is greater than 0, it prints "The number is positive." If number is less than 0, it prints "The number is negative." Otherwise, if number is exactly 0, it prints "The number is zero."

Note that you would need to include the using System; directive at the beginning of your code file to use the Console.WriteLine method.

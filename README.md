# C# Console Application - Swap Values

This is a basic C# console application that demonstrates how to swap the values of two variables.  
It covers fundamental concepts such as variable declaration, user input, and value swapping using a temporary variable or arithmetic logic.

## Description

The project includes:
- Reading two values from the user
- Swapping the values using a temporary variable
- Displaying values before and after swapping
- Optional: Swap using arithmetic or tuple assignment (in C# 7.0+)

## Technologies Used
- C#
- .NET Console Application
- Visual Studio / Visual Studio Code

## Sample Code

```csharp
// Swap two integers using a temporary variable
int a = 5, b = 10;
int temp = a;
a = b;
b = temp;

#
(int a, int b) = (5, 10);
(a, b) = (b, a);


# How to Run
Clone the repository

Open Swap.cs in Visual Studio

Build and run the program

Follow the console prompts to enter two values

# About Me
This project was created as part of my C# practice in the Makeen Bootcamp.
It highlights my understanding of variables, input/output, and simple logic in C#.

🔗 Visit my GitHub Profile

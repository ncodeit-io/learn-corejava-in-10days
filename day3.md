# 🚀 Introduction to Control Statements in Java 🚀

![Control Structures in Java — Loops | by Nickson Joram | Javarevisited |  Medium](https://miro.medium.com/v2/resize:fit:1400/1*BENOXzD3k4_-nzgYEkyDTw.png)

In Java, control statements are used to control the flow of program execution 🔀. Control statements allow programmers to create dynamic programs that can respond to changing conditions and make intelligent decisions based on data 🤖.

There are three main categories of control statements in Java:

## 🎯 Selection Statements 🎯

Selection statements are used to select one or more statements for execution based on the value of a boolean expression 💡. The two main selection statements in Java are the `if` statement and the `switch` statement.

## 🔁 Iteration Statements 🔁

Iteration statements are used to repeatedly execute a block of code as long as a certain condition is true 🔄. The three main iteration statements in Java are the `while` loop, the `do-while` loop, and the `for` loop.

## 🏃‍♂️ Jump Statements 🏃‍♂️

Jump statements are used to transfer control to a different part of the program 🏃‍♀️. The two main jump statements in Java are the `break` statement and the `continue` statement.

💡 By using control statements, programmers can write code that can respond to changing conditions and make intelligent decisions based on data. Control statements are a powerful feature of Java that allow programmers to create complex and dynamic programs. 🤖




# 🚀 Implementing Conditional Statements in Java 🤖

![Java If Statement Tutorial With Examples](https://www.softwaretestinghelp.com/wp-content/qa/uploads/2020/09/Java-if-else-if-ladder-2.png)

In Java, conditional statements allow the program to make decisions based on certain conditions. These statements evaluate a Boolean expression and execute a certain block of code if the expression is true or false. 🤔

There are two main types of conditional statements in Java: the `if` statement and the `switch` statement. 💡

## The `if` Statement

The `if` statement in Java evaluates a Boolean expression and executes a block of code if the expression is true. The basic syntax for the `if` statement is as follows:

**java code**

``` java
// Example of the if statement
int num = 10;
if (num > 0) {
    System.out.println("The number is positive");
}
```



👉 Here's an example of using the `if` statement to check if a number is even or odd:

**java code**


``` java
// Using the if statement to check if a number is even or odd
int number = 10;
if (number % 2 == 0) {
    System.out.println("The number is even");
} else {
    System.out.println("The number is odd");
}
```



🔍 In this example, the program checks if the remainder of `number` divided by 2 is equal to 0. If the remainder is 0, the program prints that the number is even. If the remainder is not 0, the program prints that the number is odd.

## The `switch` Statement

The `switch` statement in Java evaluates a variable or expression and executes a certain block of code depending on the value of the variable or expression. The basic syntax for the `switch` statement is as follows:

**java code**

``` java
// Example of the switch statement
int day = 3;
switch (day) {
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
    // other cases
    default:
        System.out.println("Invalid day");
}
```

👉 Here's an example of using the `switch` statement to print the name of a month based on its number:

**java code**


``` java
// Using the switch statement to print the name of a month
int monthNumber = 2;
switch (monthNumber) {
    case 1:
        System.out.println("January");
        break;
    case 2:
        System.out.println("February");
        break;
    // other cases
    default:
        System.out.println("Invalid month number");
}
```


🔍 In this example, the program evaluates the value of `monthNumber` and prints the name of the corresponding month. If `monthNumber` does not match any of the cases, the program prints "Invalid month number". 💥


# 😎If-else Statements in Java 😎

In programming, conditional statements allow you to execute different blocks of code based on certain conditions. One of the most fundamental conditional statements in programming is the if-else statement.

In Java, the if-else statement is used to execute a certain block of code if a given condition is true, and a different block of code if the condition is false. This is done by evaluating a Boolean expression enclosed in parentheses after the keyword `if`. If the expression is true, the code inside the curly braces immediately following the `if` statement is executed. If the expression is false, the code inside the curly braces following the `else` keyword is executed instead.

### 🚦 Syntax for If-else Statements in Java 🚦

Here's the syntax for an If-else statement in Java:

**java code**

``` java
// Syntax for the if-else statement
if (condition) {
    // block of code to be executed if the condition is true
} else {
    // block of code to be executed if the condition is false
}
```


### 🎉 Example of If-else Statements in Java 🎉

Let's take a look at an example of an If-else statement in Java:

**java code**


``` java
// Example of the if-else statement
int num = 10;
if (num > 0) {
    System.out.println("The number is positive");
} else {
    System.out.println("The number is not positive");
}
```



In this example, the program checks whether the variable `num` is greater than zero. If it is, then the program prints the message "The number is positive." If it is not, then the program prints the message "The number is not positive." 🤔

### 🤔 Multiple Conditions in If-else Statements 🤔

You can also use multiple conditions in an If-else statement using the else-if statement:

**java code**

``` java
// Using multiple conditions in an If-else statement
int number = 10;
if (number > 0) {
    System.out.println("The number is positive.");
} else if (number < 0) {
    System.out.println("The number is negative.");
} else {
    System.out.println("The number is zero.");
}
```


In this example, if the number is greater than zero, the program prints "The number is positive." If the number is less than zero, the program prints "The number is negative." If the number is equal to zero, the program prints "The number is zero." 🤩

### 🤓 Nested If-else Statements 🤓

Finally, you can also use nested If-else statements to create more complex conditions:

**java code**

``` java
// Using nested If-else statements
int num = 10;
if (num >= 0) {
    if (num == 0) {
        System.out.println("The number is zero.");
    } else {
        System.out.println("The number is positive.");
        if (num % 2 == 0) {
            System.out.println("The number is even.");
        } else {
            System.out.println("The number is odd.");
        }
    }
} else {
    System.out.println("The number is negative.");
}
```


In this example, the program checks whether the number is positive, negative, or zero, and also checks whether the number is even or odd. The program then prints out a message indicating the result. 🤯

So there you have it! If-else statements in Java are a fundamental concept in programming that allow you to create complex and dynamic code. Give it a try and see what you can create! 👨‍💻

# 🚀 If-else Statement Applications 🚀

Hey there! Are you ready to see some If-else statement applications in action? Let's dive in and explore some fun examples of how If-else statements can be used in real-world programming scenarios. 🤖💻

### 🎨 Example 1: Color Detector 🎨

Imagine you're building a program that detects the color of an object. You can use an If-else statement to determine the color of the object based on its RGB value:

**java code**


``` java
// Color Detector Example
int red = 255;
int green = 0;
int blue = 0;

if (red == 255 && green == 0 && blue == 0) {
    System.out.println("The color of the object is Red.");
} else if (red == 0 && green == 255 && blue == 0) {
    System.out.println("The color of the object is Green.");
} else if (red == 0 && green == 0 && blue == 255) {
    System.out.println("The color of the object is Blue.");
} else {
    System.out.println("The color of the object is not recognized.");
}
```



In this example, the program checks the values of `red`, `green`, and `blue` to determine the color of the object. If the values match a certain combination, then the program prints out the name of the color. If the values do not match any recognized color, then the program prints out a message saying that the color of the object is not recognized. 🌈

### 🚦 Example 2: Traffic Light Simulator 🚦

Another example of an If-else statement application is a traffic light simulator. You can use an If-else statement to simulate the different states of a traffic light:

**java code**


``` java
// Traffic Light Simulator Example
String color = "green";

if (color.equals("red")) {
    System.out.println("Stop!");
} else if (color.equals("yellow")) {
    System.out.println("Slow down.");
} else if (color.equals("green")) {
    System.out.println("Go!");
} else {
    System.out.println("Invalid color.");
}
```


In this example, the program simulates the different states of a traffic light by checking the value of the `color` variable. If the value is "red", then the program prints "Stop!" If the value is "yellow", then the program prints "Slow down." If the value is "green", then the program prints "Go!" If the value is anything else, then the program prints "Invalid color." 🚥

## **🤩 Let's create a program that can help you decide what to wear based on the weather outside! ☀️🌦️❄️**

### 🌡️ Inputting the Temperature 🌡️

The first step is to ask the user to input the current temperature. We can use the `Scanner` class to do this:

**java code**


``` java
// Inputting the Temperature
import java.util.Scanner;

public class ClothingSuggestion {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Please enter the current temperature in Fahrenheit: ");
        int temperature = scanner.nextInt();
        // Rest of the code
    }
}
```



### 🌞 Creating an If-else Statement for Hot Weather 🌞

Now that we have the temperature, we can use an If-else statement to decide what to wear based on the weather. Let's start with hot weather:

**java code**

``` java
// Creating an If-else Statement for Hot Weather
if (temperature >= 80) {
    System.out.println("It's hot outside! Wear shorts and a t-shirt.");
} 
```


If the temperature is 80 degrees Fahrenheit or higher, the program will print "It's hot outside! Wear shorts and a t-shirt." Otherwise, the program will move on to the next condition.

### 🌥️ Creating an If-else Statement for Mild Weather 🌥️

Next, let's create a condition for mild weather:

**java code**

``` java
// Creating an If-else Statement for Mild Weather
else if (temperature >= 60 && temperature <= 79) {
    System.out.println("It's mild outside! Wear a light jacket and jeans.");
} 
```

If the temperature is between 60 and 79 degrees Fahrenheit, the program will print "It's mild outside! Wear a light jacket and jeans." Otherwise, the program will move on to the next condition.

### ❄️ Creating an If-else Statement for Cold Weather ❄️

Finally, let's create a condition for cold weather:

**java code**

``` java
// Creating an If-else Statement for Cold Weather
else if (temperature < 60) {
    System.out.println("It's cold outside! Wear a coat, hat, and gloves.");
} 
```


If the temperature is less than 60 degrees Fahrenheit, the program will print "It's cold outside! Wear a coat, hat, and gloves." Otherwise, the program will move on to the next condition.

### 🌪️ Adding a Condition for Extreme Weather 🌪️

We can also add a condition for extreme weather, such as a tornado or hurricane:

**java code**

``` java
// Adding a Condition for Extreme Weather
if (temperature >= 90) {
    System.out.println("It's extremely hot outside! Stay indoors and drink water.");
} else if (temperature < 20) {
    System.out.println("It's extremely cold outside! Stay indoors and bundle up.");
} 
```


If the temperature is 90 degrees Fahrenheit or higher, the program will print "It's extremely hot outside! Stay indoors and drink water." If the temperature is less than 20 degrees Fahrenheit, the program will print "It's extremely cold outside! Stay indoors and bundle up." Otherwise, the program will move on to the next step.

### 🎉 Outputting the Final Result 🎉

Finally, we can output a message to the user letting them know what to wear:

**java code**

``` java
// Outputting the Final Result
System.out.println("Enjoy your day!");
scanner.close();
```


We can then add a print statement for each condition, depending on what the temperature is:

**java code**

``` java
// Printing a message based on the condition
if (temperature >= 90) {
    System.out.println("It's extremely hot outside! Stay indoors and drink water.");
} else if (temperature >= 80) {
    System.out.println("It's hot outside! Wear shorts and a t-shirt.");
} else if (temperature >= 60 && temperature <= 79) {
    System.out.println("It's mild outside! Wear a light jacket and jeans.");
} else if (temperature < 60 && temperature >= 20) {
    System.out.println("It's cold outside! Wear a coat, hat, and gloves.");
} else if (temperature < 20) {
    System.out.println("It's extremely cold outside! Stay indoors and bundle up.");
}
```

This code snippet prints a different message based on the temperature condition. If the temperature is extremely hot, it advises staying indoors and drinking water. For hot weather, it suggests wearing shorts and a t-shirt. For mild weather, it recommends a light jacket and jeans. For cold weather, it advises wearing a coat, hat, and gloves. If the temperature is extremely cold, it recommends staying indoors and bundling up.

# 🌟 If-else Statements: A Brief Summary 🌟

If-else statements are one of the fundamental building blocks of programming. They allow us to create conditional logic in our code and execute different blocks of code based on whether a condition is true or false. 🤔

### 🔍 How Do If-else Statements Work? 🔍

If-else statements work by first evaluating a condition. If the condition is true, a specific block of code will be executed. If the condition is false, a different block of code will be executed. This allows us to create different paths through our code, depending on the data we are working with. 🛣️

### 📝 Syntax of If-else Statements 📝

The basic syntax of an If-else statement in Java is as follows:

**java code**

``` java
int num = 10;

if(num > 0) {
    System.out.println("The number is positive.");
} else {
    System.out.println("The number is not positive.");
}
```

The `if` keyword is followed by a condition, which is usually a Boolean expression that evaluates to either `true` or `false`. If the condition is true, the code inside the first block of braces will be executed. If the condition is false, the code inside the second block of braces will be executed. 🧐

### 🌞 Example Application of If-else Statements 🌞

To see If-else statements in action, we created a fun program that helps users decide what to wear based on the weather outside. By using If-else statements, we were able to create different conditions for hot, mild, and cold weather, as well as extreme weather like tornadoes and hurricanes. 🌡️☀️🌦️❄️🌪️

If-else statements are incredibly powerful tools for creating conditional logic in our code. They allow us to make decisions based on the data we are working with, and execute different blocks of code depending on those decisions. With If-else statements, we can create programs that are more flexible, adaptable, and responsive to the world around us. 💪

# 🤔 Multiple Choice Quiz: If-else Statements 🤔

### 🌟 Question 1 🌟

What is the purpose of an if-else statement in Java?

- a. To assign a value to a variable. 
- b. To create a loop. 
- c. To execute different blocks of code depending on a condition. 
- d. To define a class.

Answer is **c. To execute different blocks of code depending on a condition.** An if-else statement allows us to create conditional logic in our code and execute different blocks of code depending on whether a condition is true or false. </details>

### 🌟 Question 2 🌟

What is the syntax for an if-else statement in Java?

- a. if (condition) { code } 
- b. if { code } else { code } 
- c. else { code } if (condition) { code } 
- d. if (condition) { code } else { code }

Answer is **d. if (condition) { code } else { code }**. The basic syntax of an if-else statement in Java consists of the `if` keyword, followed by a condition in parentheses, and then two blocks of code enclosed in curly braces. If the condition is true, the code in the first block is executed, otherwise the code in the second block is executed. 

### 🌟 Question 3 🌟

Which of the following operators is used to compare two values for equality in Java?

- a. == 
- b. != 
- c. > 
- d. <

Answer is **a. ==**. The double equals `==` operator is used to compare two values for equality in Java. The `!=` operator is used to check for inequality, while `>` and `<` are used for comparisons of greater than and less than respectively. 

### 🌟 Question 4 🌟

What is the purpose of an else-if statement in Java?

- a. To define a new class. 
- b. To execute a block of code if a previous condition is false and a new condition is true. 
- c. To create a loop. 
- d. To assign a value to a variable.

Answer is **b. To execute a block of code if a previous condition is false and a new condition is true.** An else-if statement allows us to add additional conditions to our if-else statement. If the first condition is false, the else-if statement is evaluated and if the condition is true, the corresponding block of code is executed. 

### 🌟 Question 5 🌟

Which of the following is NOT a comparison operator in Java?

- a. == 
- b. != 
- c. <= 
- d. :

Answer is **d. :**. The colon `:` is not a comparison operator in Java. The comparison operators in Java are `==` (equality), `!=` (inequality), `>` (greater than), `<` (less than), `>=` (greater than or equal to), and `<=` (less than or equal to). 

#  loops in Java! 🚀
![Loops in Java Explained - Shiksha Online](https://lh3.googleusercontent.com/ciw6Bcn98APVoP9fxhsjgHiknAQfnJr-5IQ-lTTLPth_HVIt5V60bzINZmbTjdsLdVvWkZmbJhTQoYenpBDOdGggG7Fybu1cTBc9hV1WBzR-DIKLmBDT3l02pCUqsiFD04vIpMrIqO_tclvaWA)

Loops are an essential part of programming in Java. 🤖 They allow you to execute a block of code repeatedly until a certain condition is met. 🔁

There are three types of loops in Java:

-   🟢 The **for** loop
-   🔵 The **while** loop
-   🟣 The **do-while** loop

## 🟢 For Loop

The for loop is used when you know how many times you want to execute the block of code. It has three parts: initialization, condition, and update. 🔄

## 🔵 While Loop

The while loop is used when you don't know how many times you want to execute the block of code. It checks the condition at the beginning of each iteration and continues to execute the block of code as long as the condition is true. 🤔

## 🟣 Do-While Loop

The do-while loop is similar to the while loop, but it checks the condition at the end of each iteration, so the block of code is guaranteed to execute at least once. 🤗

Loops are useful for many programming tasks, such as iterating through arrays or collections, processing data, and implementing game logic. However, be careful with loops to avoid infinite loops or inefficient code. 🤯

So, whether you are a beginner or an experienced programmer, understanding loops is a crucial part of programming in Java. 💻

# Examples: 🤗

## For Loop

🔂 The for loop is typically used when you know how many times you want to iterate over a block of code. Here's an example of a for loop that prints the numbers 1 through 5:

**java code**

``` java
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```

This code initializes the variable `i` to 1, checks if `i` is less than or equal to 5, and increments `i` by 1 after each iteration. 
The **output** of this code would be:

``` mathematicia
1 
2 
3 
4 
5
```
## While Loop

🔄 The while loop is used when you want to iterate over a block of code until a certain condition is met. Here's an example of a while loop that prints the numbers 1 through 5:

**java code**

``` java
int i = 1;
while (i <= 5) {
    System.out.println(i);
    i++;
}
```

This code initializes the variable `i` to 1, checks if `i` is less than or equal to 5, and increments `i` by 1 after each iteration. 
The **output** of this code would be the same as the for loop:
``` mathematicia
1 
2 
3 
4 
5
```




## Do-While Loop

🔁 The do-while loop is similar to the while loop, but it will always execute the block of code at least once before checking the condition. Here's an example of a do-while loop that prints the numbers 1 through 5:

**java code**

``` java 
int i = 1;
do {
    System.out.println(i);
    i++;
} while (i <= 5);
```


This code initializes the variable `i` to 1, executes the block of code once, checks if `i` is less than or equal to 5, and increments `i` by 1 after each iteration. 
The **output** of this code would be the same as the previous two examples:

``` mathematicia
1 
2 
3 
4 
5
```


By using loops in your Java code, you can simplify repetitive tasks and make your code more efficient. 💻 However, it's important to use loops carefully to avoid infinite loops or other errors that could crash your program. 😱

# Summary🔁 :

🔂 For loops are used when you know how many times you want to run a block of code.

🔄 While loops are used when you want to keep running a block of code until a certain condition is met.

🔁 Do-while loops are similar to while loops, but they always run the code at least once before checking the condition.

🎉 Using loops in Java is a great way to make your code more efficient and avoid repetitive tasks. Just be careful not to create infinite loops! 😅

# 🚀Applications of Loops:🔍

🎉 Java loops are incredibly powerful tools that allow you to repeat a block of code multiple times, depending on certain conditions. Here are some applications of Java loops:

🚀 **Automating Tasks:** Java loops can be used to automate repetitive tasks, such as printing out the elements of an array or reading through a file line-by-line.

🎓 **Learning and Practice:** Loops are a fundamental concept in programming, and practicing them in Java can help you better understand the logic behind them and improve your coding skills.

🎮 **Games and Animations:** Loops can be used to create complex games and animations, such as simulating the movement of objects or generating complex fractals.

🌍 **Data Processing and Analysis:** Loops are often used in data processing and analysis applications, such as calculating statistics or sorting data.

💻 **Efficiency:** By using loops in your Java code, you can simplify repetitive tasks and make your code more efficient, saving time and resources.

🔍 **Searching and Filtering:** Loops can be used to search through arrays or collections and filter out elements that meet certain conditions.

🎊 With so many different applications, it's clear that loops are an essential tool in any Java programmer's toolkit. So go ahead, experiment with loops and see what amazing things you can create! 🤖


# 🌟Solving Programming Problems using Loops and Conditional Statements🌟

Programming problems can be challenging, 🤔 but with the right tools, they can be solved efficiently. 🛠️ Loops and conditional statements are two essential tools in any programmer's toolkit. These tools help to automate tasks and make complex tasks more manageable. 💻

🎉 Loops are used to execute a block of code multiple times. There are three main types of loops in programming: while, for, and do-while.

🌟 A while loop continues to execute the block of code as long as the specified condition is true. A for loop is used when the number of times a block of code needs to be executed is known. A do-while loop is similar to the while loop but ensures that the code block is executed at least once before the condition is checked.

💡 Conditional statements are used to make decisions in the code. They allow the code to take different paths depending on the value of a specified condition. The two main types of conditional statements are if-else and switch-case.

🚀 An if-else statement checks a condition, and if it is true, executes one block of code, otherwise, executes another block of code. A switch-case statement checks the value of a variable and executes the corresponding block of code.

## 🔍 Let's see how we can use loops and conditional statements to solve programming problems:

### 1. Finding the sum of numbers from 1 to n:

We can use a for loop to iterate from 1 to n and add each number to a variable that holds the sum. 🌈 For example:

**java code**

``` java
int n = 10;
int sum = 0;
for (int i = 1; i <= n; i++) {
    sum += i;
}
System.out.println("Sum: " + sum);
```

### 2. Checking if a number is prime:

We can use a while loop to iterate from 2 to n/2 and check if n is divisible by any number in that range. If n is divisible by any number, it is not prime. 🌞 For example:

**java code**

``` java
int n = 17;
boolean isPrime = true;
int i = 2;
while (i <= n / 2) {
    if (n % i == 0) {
        isPrime = false;
        break;
    }
    i++;
}
if (isPrime) {
    System.out.println(n + " is a prime number.");
} else {
    System.out.println(n + " is not a prime number.");
}
```


### 3. Reversing a string:

We can use a for loop to iterate from the end of the string to the beginning and add each character to a new string variable. 🌼 For example:

**java code**

``` java
String original = "hello";
String reversed = "";
for (int i = original.length() - 1; i >= 0; i--) {
    reversed += original.charAt(i);
}
System.out.println("Reversed string: " + reversed);
```


### 4. Printing numbers from 1 to n, but for multiples of 3, print "Fizz" and for multiples of 5, print "Buzz":

We can use a for loop to iterate from 1 to n and use an if-else statement to check if the number is divisible by 3 or 5. 🌟 For example:

**java code**

``` java
int n = 20;
for (int i = 1; i <= n; i++) {
    if (i % 3 == 0 && i % 5 == 0) {
        System.out.println("FizzBuzz");
    } else if (i % 3 == 0) {
        System.out.println("Fizz");
    } else if (i % 5 == 0) {
        System.out.println("Buzz");
    } else {
        System.out.println(i);
    }
}
```


In conclusion, loops and conditional statements are powerful tools that can be used to solve a wide range of programming problems. By combining these tools with other programming concepts, such as arrays and functions, we can solve even more complex problems.


# Java Loops Quiz🚀

🤔 Test your knowledge of Java loops with these tricky multiple-choice questions! 🤔

### Question 1️⃣

Which of the following statements is true about the `do-while` loop in Java?

- A. The loop body is executed at least once. 
- B. The loop condition is checked before executing the loop body. 
- C. The loop condition is checked after executing the loop body. 
- D. The `do-while` loop is not a valid loop construct in Java.

<font color="darkgreen">**Answer:** A</font>

### Question 2️⃣

What will be the output of the following code?

**java code**

``` java
public class Example {
    public static void main(String[] args) {
        for (int i = 0; i < 5; i++) {
            if (i == 2) {
                continue;
            }
            System.out.print(i + " ");
        }
    }
}
```


- A. 0 1 2 3 4 
- B. 0 1 3 4 
- C. 2 4 
- D. 0 1 4

<font color="darkgreen">**Answer:** B</font>

### Question 3️⃣

What will be the output of the following code?

**java code**

``` java
public class Test {
    public static void main(String[] args) {
        int i;
        for (i = 0; i < 3; i++) {
            System.out.print(i + " ");
        }
    }
}
```


- A. 0 1 2 
- B. 0 1 2 3 
- C. 0 1 2 3 4 
- D. None of the above

<font color="darkgreen">**Answer:** A</font>

### Question 4️⃣

What will be the output of the following code?

**java code**

![](https://i.gyazo.com/442c1e39018c8b882630d58b69903fcf.png)


- A. 0 
- B. None 
- C. An infinite loop 
- D. A compiler error

<font color="darkgreen">**Answer:** C</font>

### Question 5️⃣

What will be the output of the following code?

**java code**

``` java
public class Main {
    public static void main(String[] args) {
        for (int i = 0; i < 5; i += 2) {
            System.out.print(i + " ");
        }
    }
}
```
 

- A. 0 2 4 6 8 
- B. 0 2 4 
- C. 0 1 2 3 4 
- D. None of the above

<font color="darkgreen">**Answer:** B</font>

🎉 Congratulations on finishing the Java Loops Quiz! 🎉


### Week 1 Open Ended Questions

Note:

-   **DO** use ChatGPT to ask where you went wrong/for feedback (i.e. paste ur current/not working code and explain the intended output, **ask ChatGPT what went wrong and _how_ to amend it**).
-   **DON'T** use ChatGPT to generate the solution before attempting. You will only be cheating yourself at the end of the day
-   I trust that you are mature enough to understand ethical use of GenAI.

#### Question 1

-   You are tasked to build an account management system.
-   Initial account size: $0.
-   Income (I) increases account size.
-   Expenditure (E) decreases account size.
-   Quit (X) exits the main logic, then prints the account balance.

The following is the sample output:

```
=== Welcome to Fake Bank ===
Please enter your choice (I for Income, E for Expenditure, X to Exit): I
Please enter the amount: 50.5
Please enter your choice (I for Income, E for Expenditure, X to Exit): E
Please enter the amount: 20
Please enter your choice (I for Income, E for Expenditure, X to Exit): I
Please enter the amount: 100
Please enter your choice (I for Income, E for Expenditure, X to Exit): X
Your account balance is $130.50
```

#

#### Question 2

-   You are tasked to build a simple calculator.
-   The calculator supports addition (A), subtraction (S), multiplication (M), and division (D).
-   Each operation should take two operands.
-   Quit (X) exits the main logic.

The following is the sample output:

```
Please enter your choice (A for Addition, S for Subtraction, M for Multiplication, D for Division, X to Exit): A
Please enter the first number: 10
Please enter the second number: 5
Result: 15
Please enter your choice (A for Addition, S for Subtraction, M for Multiplication, D for Division, X to Exit): M
Please enter the first number: 6
Please enter the second number: 7
Result: 42
Please enter your choice (A for Addition, S for Subtraction, M for Multiplication, D for Division, X to Exit): X
```

#

#### Question 3

-   You are tasked to build a grade tracking system.
-   The system should allow entering grades for different subjects.
-   The grades should be stored, and the average grade should be calculated upon exiting.
-   Quit (X) exits the main logic, then prints the average grade.

The following is the sample output:

```
Please enter your choice (G to enter Grade, X to Exit): G
Please enter the subject: Math
Please enter the grade: 85
Please enter your choice (G to enter Grade, X to Exit): G
Please enter the subject: Science
Please enter the grade: 90
Please enter your choice (G to enter Grade, X to Exit): G
Please enter the subject: History
Please enter the grade: 78
Please enter your choice (G to enter Grade, X to Exit): X
Your average grade is 84.33
```

#

#### Question 4

You are helping a bakery calculate their daily requirements. They need a program that calculates the cost of ingredients for a batch of cookies, the total calories of a batch of cookies, and the total cost of production.

Requirements:

-   You are building a simple calculator for a small shop.
-   The shop needs to calculate the total cost of items purchased, the discount applied, and the final amount after discount.

```c
#include <stdio.h>

// Function to calculate the total cost of items
float total_cost(float price1, int quantity1, float price2, int quantity2) {
    // implement it yourself
}

// Function to calculate the discount amount
float discount_amount(float total_cost, float discount_percentage) {
    // implement it yourself
}

// Function to calculate the final amount after discount
float final_amount(float total_cost, float discount_amount) {
    // implement it yourself
}

int main() {
    // implement it yourself
    // create your own journey, no hand holding here
    return 0;
}

```

#### Question 5

-   You are tasked to build a temperature conversion tool.
-   The tool should convert temperatures between Celsius (C) and Fahrenheit (F).
-   The user should specify the type of conversion and the temperature to convert.
-   Quit (X) exits the main logic.
-   You are given the formulae. You are **required** to create a function to convert it to keep code clean

```**
fahrenheit = (9/5)*celcius + 32
celsius = (fahrenheit-32) * (5/9)
```

Sample usage of function:

```c
// create the function with a unique name

float celsiusToFahrenheit(float celsius){
    float fahrenheit = (9/5)*celcius + 32;
    return fahrenheit
}

int main(){
    float celsius = 10;
    // invoke the function to convert celsius to float
    // assign the value to the newly created fahrenheit variable
    float fahrenheit = celsiusToFahrenheit(celsius);
    printf("fahrenheit temp is %f\n", fahrenheit);
}
```

The following is the sample output:

```
Please enter your choice (C for Celsius to Fahrenheit, F for Fahrenheit to Celsius, X to Exit): C
Please enter the temperature in Celsius: 25
Temperature in Fahrenheit: 77.0
Please enter your choice (C for Celsius to Fahrenheit, F for Fahrenheit to Celsius, X to Exit): F
Please enter the temperature in Fahrenheit: 98.6
Temperature in Celsius: 37.0
Please enter your choice (C for Celsius to Fahrenheit, F for Fahrenheit to Celsius, X to Exit): X
```

#

#### Question 5

-   You are tasked to build a grade analysis system for a class.
-   The system should allow entering grades for students.
-   The system should count the number of A's (100-80), B's (79-65), C's (64-50), and failures (grades below 50).
-   The system should also calculate the average grade.
-   Quit (X) exits the main logic, then prints the counts and the average grade.
-   You are required to create a function to handle the logic with the following function prototype

```c
char getGradeFromScore(float score){
    char grade;
    // implementation here (all your if else's)
    return grade;
}
```

The following is the sample output:

```
Please enter your choice (G to enter Grade, X to Exit): G
Please enter the grade: 85
Please enter your choice (G to enter Grade, X to Exit): G
Please enter the grade: 90
Please enter your choice (G to enter Grade, X to Exit): G
Please enter the grade: 78
Please enter your choice (G to enter Grade, X to Exit): G
Please enter the grade: 45
Please enter your choice (G to enter Grade, X to Exit): X
Number of A's: 2
Number of B's: 1
Number of C's: 0
Number of Failures: 1
Average grade: 74.5
```

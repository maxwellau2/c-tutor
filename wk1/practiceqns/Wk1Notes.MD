### Basics of C Programming

#### Variables

Variables are used to store data that can be manipulated by the program. In C, you must declare a variable before you use it.

**Declaration:**

```c
int age; // Declares an integer variable named age
float salary; // Declares a floating-point variable named salary
char grade; // Declares a character variable named grade
```

**Initialization:**

```c
int age = 25; // Declares and initializes age with 25
float salary = 50000.0; // Declares and initializes salary with 50000.0
char grade = 'A'; // Declares and initializes grade with 'A'
```

**Usage:**

```c
#include <stdio.h>

int main() {
    int age = 25;
    printf("Age: %d\n", age);
    return 0;
}
```

#### Conditionals

Conditionals are used to perform different actions based on different conditions.

**If Statement:**

```c
#include <stdio.h>

int main() {
    int age = 20;
    if (age >= 18) {
        printf("Adult\n");
    }
    return 0;
}
```

**If-Else Statement:**

```c
#include <stdio.h>

int main() {
    int age = 16;
    if (age >= 18) {
        printf("Adult\n");
    } else {
        printf("Not an adult\n");
    }
    return 0;
}
```

**Else-If Ladder:**

```c
#include <stdio.h>

int main() {
    int score = 85;
    if (score >= 80) {
        printf("Grade A\n");
    } else if (score >= 65) {
        printf("Grade B\n");
    } else if (score >= 50) {
        printf("Grade C\n");
    } else {
        printf("Grade F\n");
    }
    return 0;
}
```

#### While Loops

While loops are used to repeat a block of code as long as a specified condition is true.

**Syntax:**

```c
#include <stdio.h>

int main() {
    int i = 0;
    while (i < 5) {
        printf("%d\n", i);
        i++;
    }
    return 0;
}
```

**Example with Condition:**

```c
#include <stdio.h>

int main() {
    int number = 1;
    while (number != 0) {
        printf("Enter a number (0 to exit): ");
        scanf("%d", &number);
        printf("You entered: %d\n", number);
    }
    return 0;
}
```

#### Functions

Functions are blocks of code that perform a specific task and can be reused.

**Function Declaration:**

```c
return_type function_name(parameter_list);
```

**Function Definition:**

```c
#include <stdio.h>

// Function declaration
int add(int a, int b);

int main() {
    int sum = add(3, 4);
    printf("Sum: %d\n", sum);
    return 0;
}

// Function definition
int add(int a, int b) {
    return a + b;
}
```

**Function with No Return Type:**

```c
#include <stdio.h>

// Function declaration
void printHello();

int main() {
    printHello();
    return 0;
}

// Function definition
void printHello() {
    printf("Hello, World!\n");
}
```

### Summary

1. **Variables**: Used to store data, must be declared and can be initialized.
2. **Conditionals**: Used to perform actions based on conditions (`if`, `if-else`, `else-if`).
3. **While Loops**: Used to repeat actions while a condition is true.
4. **Functions**: Blocks of reusable code that perform specific tasks, can take parameters and return values.

Understanding these basics will help you build more complex programs in C and prepare you for your exams. Practice writing small programs that utilize these concepts to reinforce your learning.

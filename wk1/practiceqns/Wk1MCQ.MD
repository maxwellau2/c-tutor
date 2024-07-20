### Basic C Multiple Choice Questions

#### Question 1:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int a = 5, b = 3;
    int result = a + b * 2;
    printf("%d\n", result);
    return 0;
}
```

a) 11  
b) 16  
c) 13  
d) 8

**Answer:** a) 11

#### Question 2:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int x = 10;
    if (x > 5) {
        printf("Hello ");
    }
    if (x < 15) {
        printf("World!");
    }
    return 0;
}
```

a) Hello  
b) World!  
c) Hello World!  
d) (No output)

**Answer:** c) Hello World!

#### Question 3:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int x = 10, y = 20;
    int result = (x > y) ? x : y;
    printf("%d\n", result);
    return 0;
}
```

a) 10  
b) 20  
c) 0  
d) (No output)

**Answer:** b) 20

#### Question 4:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int i;
    for (i = 0; i < 5; i++) {
        if (i == 3) {
            break;
        }
        printf("%d ", i);
    }
    return 0;
}
```

a) 0 1 2  
b) 0 1 2 3  
c) 1 2 3  
d) 0 1 2 3 4

**Answer:** a) 0 1 2

#### Question 5:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int i = 0;
    while (i < 3) {
        printf("%d ", i);
        i++;
    }
    return 0;
}
```

a) 0 1 2  
b) 0 1 2 3  
c) 1 2 3  
d) 0 1 2 3 4

**Answer:** a) 0 1 2

#### Question 6:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int a = 5;
    int b = 2;
    printf("%d\n", a / b);
    return 0;
}
```

a) 2  
b) 2.5  
c) 3  
d) (Compile error)

**Answer:** a) 2

#### Question 7:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int x = 5;
    int y = ++x * 10;
    printf("%d\n", y);
    return 0;
}
```

a) 50  
b) 60  
c) 10  
d) 55

**Answer:** b) 60

#### Question 8:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int a = 5;
    printf("%d\n", a == 5);
    return 0;
}
```

a) 5  
b) 1  
c) 0  
d) (No output)

**Answer:** b) 1

#### Question 9:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int a = 1;
    int b = 1;
    if (a == 1 && b == 1) {
        printf("Yes\n");
    } else {
        printf("No\n");
    }
    return 0;
}
```

a) Yes  
b) No  
c) (No output)  
d) (Compile error)

**Answer:** a) Yes

#### Question 10:

What is the output of the following code?

```c
#include <stdio.h>

int main() {
    int a = 5;
    a += 5;
    printf("%d\n", a);
    return 0;
}
```

a) 5  
b) 10  
c) 15  
d) 0

**Answer:** b) 10

#### Question 11: Simple Addition Function

What will be the output of the following program?

```c
#include <stdio.h>

int add(int a, int b) {
    return a + b;
}

int main() {
    int result = add(15, 10);
    printf("Result: %d\n", result);
    return 0;
}
```

a) `Result: 15`  
b) `Result: 25`  
c) `Result: 10`  
d) `Result: 150`

**Answer:** b) `Result: 25`

#### Question 12: Absolute Value Function

What will be the output of the following program?

```c
#include <stdio.h>

int absolute(int num) {
    if (num < 0) {
        return -num;
    }
    return num;
}

int main() {
    int result = absolute(-7);
    printf("Absolute: %d\n", result);
    return 0;
}
```

a) `Absolute: -7`  
b) `Absolute: 7`  
c) `Absolute: 0`  
d) `Absolute: -0`

**Answer:** b) `Absolute: 7`

#### Question 13: Multiplication Function

What will be the output of the following program?

```c
#include <stdio.h>

int multiply(int x, int y) {
    return x * y;
}

int main() {
    int result = multiply(5, 4);
    printf("Product: %d\n", result);
    return 0;
}
```

a) `Product: 9`  
b) `Product: 20`  
c) `Product: 5`  
d) `Product: 40`

**Answer:** b) `Product: 20`

#### Question 14: Power Function

What will be the output of the following program?

```c
#include <stdio.h>

int power(int base, int exponent) {
    int result = 1;
    for (int i = 0; i < exponent; i++) {
        result *= base;
    }
    return result;
}

int main() {
    int result = power(2, 4);
    printf("Power: %d\n", result);
    return 0;
}
```

a) `Power: 8`  
b) `Power: 16`  
c) `Power: 12`  
d) `Power: 20`

**Answer:** b) `Power: 16`

#### Question 15: String Length Function

What will be the output of the following program?

```c
#include <stdio.h>

int string_length(char str[]) {
    int length = 0;
    while (str[length] != '\0') {
        length++;
    }
    return length;
}

int main() {
    int length = string_length("C Programming");
    printf("Length: %d\n", length);
    return 0;
}
```

a) `Length: 12`  
b) `Length: 13`  
c) `Length: 15`  
d) `Length: 16`

**Answer:** a) `Length: 13`

#### Question 16: Check Positive or Negative

What will be the output of the following program?

```c
#include <stdio.h>

int check_sign(int num) {
    if (num > 0) {
        return 1;
    } else if (num < 0) {
        return -1;
    } else {
        return 0;
    }
}

int main() {
    int result = check_sign(-10);
    printf("Sign: %d\n", result);
    return 0;
}
```

a) `Sign: 1`  
b) `Sign: -1`  
c) `Sign: 0`  
d) `Sign: -10`

**Answer:** b) `Sign: -1`

#### Question 17: Average Function

What will be the output of the following program?

```c
#include <stdio.h>

float average(float a, float b) {
    return (a + b) / 2;
}

int main() {
    float result = average(7.0, 13.0);
    printf("Average: %.2f\n", result);
    return 0;
}
```

a) `Average: 10.00`  
b) `Average: 20.00`  
c) `Average: 14.00`  
d) `Average: 8.00`

**Answer:** a) `Average: 10.00`

#### Question 18: Area of Rectangle

What will be the output of the following program?

```c
#include <stdio.h>

int area_of_rectangle(int width, int height) {
    return width * height;
}

int main() {
    int area = area_of_rectangle(5, 7);
    printf("Area: %d\n", area);
    return 0;
}
```

a) `Area: 35`  
b) `Area: 12`  
c) `Area: 50`  
d) `Area: 42`

**Answer:** a) `Area: 35`

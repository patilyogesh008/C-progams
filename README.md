# C Loops Examples

This repository contains examples of different types of loops in C programming.

## Table of Contents
- [Introduction](#introduction)
- [Types of Loops](#types-of-loops)
  - [For Loop](#for-loop)
  - [While Loop](#while-loop)
  - [Do-While Loop](#do-while-loop)
- [Usage](#usage)
- [License](#license)

## Introduction
Loops in C are used to execute a block of code repeatedly as long as a specified condition is true. This repository demonstrates the three main types of loops in C: `for`, `while`, and `do-while`.

## Types of Loops

### For Loop
```c
#include <stdio.h>

int main() {
    for (int i = 1; i <= 5; i++) {
        printf("Iteration %d\n", i);
    }
    return 0;
}
```

### While Loop
```c
#include <stdio.h>

int main() {
    int i = 1;
    while (i <= 5) {
        printf("Iteration %d\n", i);
        i++;
    }
    return 0;
}
```

### Do-While Loop
```c
#include <stdio.h>

int main() {
    int i = 1;
    do {
        printf("Iteration %d\n", i);
        i++;
    } while (i <= 5);
    return 0;
}
```

## Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/c-loops-examples.git
   ```
2. Navigate to the project directory:
   ```sh
   cd c-loops-examples
   ```
3. Compile and run any C program using GCC:
   ```sh
   gcc for_loop.c -o for_loop && ./for_loop
   ```

## License
This project is licensed under the MIT License. Feel free to modify and use it as needed.

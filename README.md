# C tutorials

- [Link](https://www.tutorialspoint.com/cprogramming/index.htm)

### Initial checks

- Run gcc -v to check the version of c compiler installed(on linux)

### Hello World program

```C
#include <stdio.h>

int main() {
	/* my first program in C */
	printf("Hello World!\n");

	return 0;
}

/*
# compiles the code
gcc c-tutorials-tutorialspoint.c

# runs the output program
./a.out

# program output
Hello World!
*/
```

### Tokens in C

- A C program consists of various tokens and a token is either a keyword, an identifier, a constant, a string literal, or a symbol. For example, the following C statement consists of five tokens

```C
printf("Hello, World! \n");
```

- The individual tokens are
```C
printf
(
"Hello, World! \n"
)
;
```

### Semicolons

- In a C program, the semicolon is a statement terminator

### Comments

- Comments start with `/*` and terminate with the characters `*/`

### Identifiers

- A C identifier is a name used to identify a variable, function, or any other user-defined item. An identifier starts with a letter A to Z, a to z, or an underscore '`_`' followed by zero or more letters, underscores, and digits (0 to 9)
- C does not allow punctuation characters such as @, $, and % within identifiers. C is a case-sensitive programming language

### Keywords

- [Certain](https://www.tutorialspoint.com/cprogramming/c_basic_syntax.htm) words are reserved in C and may not be used for naming variables

### Whitespace in C

- Whitespace is the term used in C to describe blanks, tabs, newline characters and comments
- Whitespace separates one part of a statement from another and enables the compiler to identify where one element in a statement, such as int, ends and the next element begins

```C
int age;
fruit = apples + oranges;   // get the total fruit
```


### Data types
- 

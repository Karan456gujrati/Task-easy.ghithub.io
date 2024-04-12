# XLang

XLang is a modern programming language designed for simplicity, efficiency, and flexibility. It is suitable for a wide range of applications, from web development to system programming.

## Features

- Simple syntax inspired by familiar programming languages like Python and JavaScript
- Strongly-typed with type inference for concise code
- Object-oriented programming support with classes and inheritance
- Functional programming features such as first-class functions and lambda expressions
- Seamless interoperability with existing libraries written in other languages
- Fast execution speed with a lightweight runtime environment

## Getting Started

To start using XLang, follow these steps:

1. **Installation**: XLang can be installed on your system by downloading the compiler and runtime from the official website or using a package manager.

2. **Hello World**: Write your first XLang program by creating a new file with the `.x` extension and writing the following code:

    ```xlang
    // hello.x
    function main() {
        print("Hello, World!");
    }
    ```

3. **Compile and Run**: Use the XLang compiler to compile your program:

    ```bash
    xlangc hello.x -o hello
    ```

    Then run the compiled executable:

    ```bash
    ./hello
    ```

4. **Explore Documentation**: Refer to the official documentation and tutorials on the XLang website to learn more about the language features and how to use them effectively.

## Example

Here's an example of a simple class definition in XLang:

```xlang
class Person {
    let name: String;
    let age: int;

    function constructor(name: String, age: int) {
        this.name = name;
        this.age = age;
    }

    function greet() {
        print("Hello, my name is " + this.name + " and I am " + this.age + " years old.");
    }
}

let person = new Person("Alice", 30);
person.greet();

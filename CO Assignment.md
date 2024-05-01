# Addressing Modes 

## Modes of Addressing:

   The various methods a computer architecture might designate operand locations for instructions are referred to as addressing modes. Among them are the following: indexed, relative, direct, indirect, and immediate modes. For particular programming styles and operation kinds, each mode has benefits.

## Fixed Points:

Basic components of programming languages are variables and constants:

1. Variables: These are symbols for values that are subject to change while a program is being executed. Generally, they are defined with a particular data type, and as the program progresses, they can be given new values. The amount of memory space allotted to variables during implementation is contingent upon the nature of the data.

 As an illustration:
   
   int x; x = 5; // Declaration of an integer variable named x Putting a number on x

2. Constants: These are values that don't change while a program is being executed. In numerous programming languages, the `const` keyword is utilized to declare them.

   As an illustration:
   
   PI = 3.14159 # A constant with the name PI is declared.
   
Variables and constants are similarly kept in memory; the primary distinction is that a variable's value might change while the program is running, whereas a constant's value never changes.

## Inspiration and Guidance:  
  Programming principles of indirection and pointers are tightly related, particularly in languages like C and C++. 

1. Indirection: The capacity to indirectly access a value via a reference or a higher level of abstraction is known as indirection. Instead than accessing the data directly, it enables you to manipulate it indirectly by using a pointer or reference.

2. Pointers: Pointers are variables that hold addresses in memory. By enabling you to read and modify data stored at a particular memory region indirectly, they enable indirection. Pointers are strong dynamic memory tools.

## Instance in C:

#include <stdio.h> 
int main() {
int x = 10; // Declare an integer variable
int *ptr; // Declare a pointer to an integer
ptr = &x;
printf("Value of x: %d\n", x);
printf("Value of x via pointer: %d\n", *ptr); 
printf("New value of x:%d\n",x); 
return 0; 
}

## Using arrays and indexing:

   Fundamental ideas in programming, particularly in languages like Python and C, are indexing and arrays.

1. Indexing: Indexing is the process of gaining access to specific items in a data structure, like lists, arrays, or strings. Depending on the programming language, each element in the data structure is given a distinct index or location, which starts at 0 or 1.

2. Arrays: An array is a group of identically typed elements kept in a series of memory locations. An array's elements can be accessed by using their index. A fixed-size collection of data can be easily stored and managed with the help of arrays.

 ## a basic Python example

Using indexing to access items print("Element at index 0:", arr[0]) 
Output: 10 print(arr[2]), "Element at index 2:") 
Outcome: 30

## 1)Indexed addressing modes :

  Indexed addressing modes, which are frequently used to access members of arrays or data structures,
entail appending an index or offset value to a base address kept in a register in order to effectively access operands in memory.

![WhatsApp Image 2024-05-01 at 10 17 34 PM](https://github.com/sivasubramanian-07/Addressing-Modes/assets/168350041/23b8872e-a24b-4117-aa6d-7f0708570b34)


## (2)Immediate addressing mode :

   The operand is defined in the instruction itself in this style. Although the instructions are lengthier, it is easy to identify the operands.

   ![WhatsApp Image 2024-05-01 at 10 17 33 PM](https://github.com/sivasubramanian-07/Addressing-Modes/assets/168350041/38b29b4a-d3dc-4c3a-a48c-6c0b5fda1765)


## 3)Register Direct Addressing Mode:

   In this manner, a register is used to directly specify the operand for an instruction.Rather than using a memory address, instructions make reference to the contents of a register.

![WhatsApp Image 2024-05-01 at 10 17 51 PM](https://github.com/sivasubramanian-07/Addressing-Modes/assets/168350041/c8afe309-e955-49fd-ae25-acfe1ff09c2a)


## (4) Register  indirect addressing mode :

   ln this technique, a register is used to indirectly specify the operand's address.The instruction contains the address of a memory region where the operand is stored, as opposed to accessing the operand's value directly.The operand's position in memory is indicated by the register.

   ![WhatsApp Image 2024-05-01 at 10 17 52 PM](https://github.com/sivasubramanian-07/Addressing-Modes/assets/168350041/14ed1e5d-3d48-4207-b5ba-f2ee9685d8c7)


## (5)Relative addressing modes :

  The operand's address is specified in relation to the program counter or instruction pointer using the relative addressing mode, which makes program relocation easier and allows for more flexible and effective execution—particularly for instructions that branch or jump.

  ![WhatsApp Image 2024-05-01 at 10 17 52 PM (1)](https://github.com/sivasubramanian-07/Addressing-Modes/assets/168350041/eb548bf4-044d-4580-84c5-6e983ac28913)


Conclusion :

   Determining how instructions express operands in machine language requires knowledge of addressing modes. They include a variety of registers, including indexed, relative, indirect, and direct. Every mode has distinct advantages that affect memory access, flexibility, and efficiency. Selecting the appropriate addressing mode is essential for maximizing memory consumption and program performance
 
   






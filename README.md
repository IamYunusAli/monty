<h1> Monty: C - Stacks, Queues - LIFO, FIFO:</h1>
The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:

<h1>concept covered</h1>
What do LIFO and FIFO mean.<br>
What is a stack, and when to use it.<br>
What is a queue, and when to use it.<br>
What are the common implementations of stacks and queues.<br>
What are the most common use cases of stacks and queues.<br>
What is the proper way to use global variables.<br>
<h1>opcodes</h1>
 <code>
     - Push an elements to the stack.<br>
     - Prints all the values on the stack, starting from the top of the stack.<br>
     - Prints the value at the top of the stack, followed by a new line.<br>
     - Removes the top element of the stack.<br>
     - Swaps the top two elements of the stack.<br>
     - Adds the top two elements of the stack.<br>
     - Subtracts the top element of the stack from the second top element of the stack.<br>
     - Divides the second top element of the stack by the top element of the stack.<br>
     - Multiplies the second top element of the stack with the top element of the stack.<br>
     - Computes the rest of the division of the second top element of the stack by the top element of the stack.<br>
     - Prints the char at the top of the stack, followed by a new line.<br>
     - Prints the string starting at the top of the stack, followed by a new line.<br>
     - Rotates the stack to the top.<br>
     - Rotates the stack to the bottom.<br>
     - Sets the format of the data to a stack (LIFO). This is the default behavior of the program.<br>
     - Sets the format of the data to a queue (FIFO).<br>
 </code>
<h1>Author</h1>

[Yunus Ali](https://github.com/iamyunusali)

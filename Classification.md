# SILVER - _EXAM STYLE QUESTIONS_
 
 1. *Why a developer, who is good at both low-level and high-level programming languages, would normally use a high-level language when writing programs? (4 Marks)*

I think they use a difficult language because this types of languages are able to give them a maximum flexibility to abstract or to be literal. 

2.  *What is a machine code? (1 mark)*

Is a strictly numerical language which is intended to run as fast as possible, and it may be regarded as the lowest-level representation of a compiled or assembled computer program or as a primitive and hardware-dependent programming language.

3. Give an example of high level language. (1 mark)

An example of a high level language it is Java language. 

# GOLD - _ANSWER THE FOLLOWING QUESTIONS_

1. Describe three differences between low-level language and high-level languages? (6 Marks)  

**Low-level languages** are characterized by offering the programmer total control over the hardware on which it runs, allowing the maximum speed and capabilities of the computer to be achieved.
While **high-level languages** they seek to be independent of the hardware they run on, hiding their complexities from the programmer so that he can focus on the problem to be solved. 

2. What does a translator do? (2 Marks)  

A translator is a program that converts source code into object code.

3. Identify two types of translators that can turn high-level languages into machine code? (4 Marks)

- A **compiler**, is a translator used to convert high-level programming language to low-level programming language.
- **Interpreter**, is a translator used to convert high-level programming language to low-level programming language. It converts the program one at a time and reports errors detected at once, while doing the conversion.


# PLATINUM - *EXAM QUESTIONS*

1. What is the difference between an interpreter and a compiler? (4 Marks)  
* Interpreter
-- Translates just one statement of the program at a time into machine code.
-- Takes very less time to analyze the source code
-- Does not generate an intermediary code. 
* Compiler
-- Scans the entire program and translates the whole of it into machine code at once.
-- Takes a lot of time to analyze the source code. 
-- Always generates an intermediary object code.

2. What is assembly language? (2 Marks)  

An **assembly language** is a low-level programming **language** designed for a specific type of processor. It may be produced by compiling source **code** from a high-level programming **language** (such as C/C++) but can also be written from scratch. **Assembly code** can be converted to machine **code** using an **assembler**

3. A developer is writing a program.  

a) The program is written in a high-level language and it is then translated into machine code. Describe two differences between high-level language and machine code? (2 Marks)  

Machine language, or machine code, is the only language that is directly understood by the computer, and it does not need to be translated. All instructions use binary notation and are written as a string of 1s and 0s. A program instruction in machine language may look something like this:
```c
10010101100101001111101010011011100101 
```
 
A high-level language is a programming language that uses English and mathematical symbols, like +, -, % and many others, in its instructions. When using the term 'programming languages,' most people are actually referring to high-level languages. High-level languages are the languages most often used by programmers to write programs. Examples of high-level languages are C++, Fortran, Java and Python.

To get a flavor of what a high-level language actually looks like, consider an ATM machine where someone wants to make a withdrawal of $100. This amount needs to be compared to the account balance to make sure there are enough funds. The instruction in a high-level computer language would look something like this:

```c
  x = 100 

 if balance x: 
  print 'Insufficient balance' 

 else: 

print 'Please take your money' 
```

This is not exactly how real people communicate, but it is much easier to follow than a series of 1s and 0s in binary code.

There are a number of advantages to high-level languages.

The first advantage is that high-level languages are much closer to the logic of a human language.

The second advantage is that the code of most high-level languages is portable and the same code can run on different hardware

b) One type of translator is an interpreter.  

i) Describe how an interpreter translates high-level language programs into machine code? (1 Mark)  

An **interpreter translates code into machine code**, instruction by instruction - the CPU executes each instruction before the **interpreter** moves on **to translate** the next instruction. Interpreted **code** will show an error as soon as it hits a problem, so it is easier **to** debug than compiled **code**.

ii) State the name of a different type of translator that can be used to translate high-level code into machine code? (1 Mark)

Compilers **convert high**-**level language code** to **machine** (object) **code** in one session. Compilers **can** take a while, because they have to **translate high**-**level code** to lower-**level machine language** all at once and then save the executable object **code** to memory.



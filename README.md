# Low and High level language

### The earliest electronic computers could only be programmed with low-level languages. Programs written in low-level languages are specific to the type of processor they are written for and directly affect the computer’s processor. There are two categories of low-level language: machine code and assembly language. 

## Machine Code

- Machine code uses only the binary digits 1​ and 0​ to represent instructions. This makes 
programs written in machine code very long and extremely difficult for humans to 
understand. Because of this, machine code programs are prone to errors and difficult to 
debug. 

- Because machine code directly manipulates a computer’s processor, it is a very powerful 
paradigm. Programmers are not constrained when using machine code. Furthermore, 
there is no need to translate machine code before executing it, making the paradigm 
useful for embedded systems and real-time applications where speed of execution is 
paramount. 

## Assembly language

- Assembly language is a ‘low-level’ programming language, each instruction performs a very simple operation, and it might take many such instructions to match the functionality of a single line of code in a ‘high-level’ language (such as Python, VB, or C#). 
- Each instruction in assembly language corresponds to an operation that can be executed directly by electronic circuits in the processor. Different processors therefore have different assembly languages, though there are many common features.
- A processor can’t execute the assembly language directly: each line of code must be translated into a ‘machine code’ first – a process known as ‘assembling’ and the tool for performing the conversion is known as an assembler – but each assembly language instruction results in one 32-bit code. 

- Assembly language was developed with the intention of simplifying the process of writing computer programs. Mnemonics, such as ADD​ and MOV​, are used in place of the binary instructions that machine code uses. This makes assembly language more compact and less error prone than machine code.

- Each assembly language instruction has a 1-to-1 correlation to a machine code instruction. For example, the assembly language instruction MOV R2, R1​ might be the exact equivalent of the machine code instruction 11011101​

![image](https://github.com/Minwauu/Assembly-Language/assets/110039102/70021065-3efd-4407-b5cf-cafecf837cd8)

## High level language

- Unlike low-level languages, high-level languages are not platform specific. However, high-level languages must be translated into machine code by a compiler or an interpreter before they can be executed.

- High-level languages don’t use binary digits or mnemonics but use English instructions like “While” and mathematical symbols like “+”. This makes high-level languages much easier for humans to learn and understand as well as making them easier to debug. 

- Most high-level languages allow programmers to make use of built-in functions. These can save vast amounts of time when programming. 

- Features such as named variables, indentation and commenting make programs written in high-level languages far easier to debug than those written in low-level languages.

- High-level languages include imperative high-level languages. In a similar way to low-level languages, imperative high-level languages are formed from instructions that specify how the computer should complete a task, in contrast to declarative programming which describes what a computer should do. 

![image](https://github.com/Minwauu/Assembly-Language/assets/110039102/d8581d2e-0eb8-4a23-b754-8e97253374f7)

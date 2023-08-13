---
layout: post
title:  "15. Programming basic"
date:   2023-08-05 20:07:47 -0700
categories: jekyll update
---

## Types of code 
- Source code
	- Write a program in the text format.
	- It can not be run.
- Object code
	- text-formatted code needs to be converted to machine language.
	- It can not be run.
- Executable code
	- Address information must be included in order for object code to be loaded onto memory.
	- It is created by linking the generated object code with the used libraries.

## Compile procedure
### Compile
- The process of converting a source code in the form of text into an object code in the form of machine language that the CPU can understand.
- Do not know where to load the actual memory.
- Processing the phrases with # (#include, #define)


![Screenshot from 2023-08-12 18-41-38](/img/Screenshot from 2023-08-12 18-41-38.png)

### Linking
- Convert objective codes to executable code for the operating system.
- Connecting multiple object codes and used libraries into one executable code.
- Adding information to recall library routines.
- Adding address information for location to place executable code in physical memory because executable code must be loaded on memory to execute it.

![Screenshot from 2023-08-12 18-38-54](/img/Screenshot from 2023-08-12 18-38-54.png)

### Build
- processing the compiling and linking together.

### Loading
- The loader places an executable code on the main memory.
- A program is processed by CPU after being registered in the kernel

## Compiler
- GCC
	- C compiler provided by Linux (GNU CCompiler)
	- Basically, it is installed in the directory /usr/local/bin
	- \# gcc [option] [filename]
	- when compiling without options, it generates an executable code named a.out.
	- Option
		- -c : generate only an object file. (filename.o)
		- -o [filename] : generate an executable file with the specified name.
		- -L [path name] : specifying a library path that is not a standard library location.
		- -I [path name] : specifying a header file path that is not a standard location of header files.

![Screenshot from 2023-08-13 11-59-09](/img/Screenshot from 2023-08-13 11-59-09.png)

![Screenshot from 2023-08-13 11-53-31](/img/Screenshot from 2023-08-13 11-53-31.png)


---
layout: post
title:  "14. Shell programming"
date:   2023-08-05 20:07:47 -0700
categories: jekyll update
---

## Basic
   
- Execute multiple commands in a predetermined order
- Interpreted and executed at run-time without compiling separately.
- Variables, Condition statement, Loop statement, etc. can be used.
- Run immediately in text file form using the vim editor.
- #! 
  - Execute the shell grammar of the following path.
- .sh
  - The shell script extension is .sh, and it is executed using sh


![Screenshot from 2023-08-12 15-22-36](/img/Screenshot from 2023-08-12 15-22-36.png)



## .bash
   
- .bashrc is a Bash shell script that Bash runs whenever it is started interactively. It initializes an interactive shell session. You can put any command in that file that you could type at the command prompt.


## Variable
   ## (1) Input & Output
      - The shell does not pre-declare a variable before it is used, and the variable is automatically created when the variable is assigned the first value.
      - All variables are treated as strings.
      - There must be no spaces on the left and right sides of = when substituting a variable.
      - Use a ‘read’ statement to receive a value for a variable.
      - To substitute a string with spaces, tie it with “ “.
      - To output a value in a variable, use $[variable name]
      - To output the character $, tie it with ‘$’ or add \ before it.
      
![Screenshot from 2023-08-12 15-43-22](/img/Screenshot from 2023-08-12 15-43-22.png)

   ### (2) Numeric
      - Make sure to add expr to calculate the value of a variable as a number, and tie them with `.
      - When parentheses ‘(‘ or ‘)’ or multiplication ‘*’ are used, add ‘\’ before it.
      - Put a space between an operator and an operand.

![Screenshot from 2023-08-12 16-04-30](/img/Screenshot from 2023-08-12 16-04-30.png)

   ### (3) Environment Variable
      - Pre-set variables suitable for the system environment.
      - It consists of uppercase letters to differentiate it from user variables.
      - The values of these variables may differ depending on the individual setting of users.
      - The value can be checked using : echo &[environment variable name]
      - The value can change using : export [environment variable name]=[value]

![Screenshot from 2023-08-12 18-16-25](/img/Screenshot from 2023-08-12 18-16-25.png)

   ### (4) Parameter Variable
      - If the script receives parameters, additional variables are created.
      - The parameters are in the form of $0, $1, $2, …

![Screenshot from 2023-08-12 18-21-53](/img/Screenshot from 2023-08-12 18-21-53.png)

![Screenshot from 2023-08-12 18-29-58](/img/Screenshot from 2023-08-12 18-29-58.png)

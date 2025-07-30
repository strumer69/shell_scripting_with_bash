# shell_scripting_with_bash
For exercise Shell_Scripting  
* ### ex1.bash --> write a bash file to print "hello world at output"-->
* touch ex1.bash (to make an empty script ) --> use (nano) for editing the file. 
* write the default first line in bash scripting --> #!/bin/bash --> which is called Shebang
* --> echo "hello world." --> run the script from the command line--> bash ./ex1.bash
* -
* -
* ### Question--> how to  make your script excutable:
* answer--> chmod +x filename.bash --> all users can execute
*           chmod u+x filename.bas --> only use can execute
*           chmod -x filename.bas  --> remove execute for all
*           chmod o-x filename.bas --> remove execute for others
*           chmod a-w filename.bas --> remove write for all
*           chmod u-w filename.bas --> remove write forowner
*       
* ### ex2.bash --> write a bash file to get the name of the user and say hello to him/her? page 23/69
* instead of the following two line of code:
*   - echo "please enter your name"
*   - read name
* we can write one line as below:
*   - read -p " please enter your name: " name
* #### multiple inputs: page 25/69
*   - echo "please enter your name and age" name age
    - echo "hello &name . you are &age years old."
* ###  silent input (password) page 26/69 --> write an script and ask user to enter password. the pass should be invisble.
* --> answer: refer to ex3.bash
* ### ex4.bash --> write a bash file execute the following items:
* print the name of bash file using ( arfument $0)
* print the first, second and 3th argument(provided you enter argument while calling your script: for example--> "bash ex4.bash hello bash world")
* print number of arguments.
* print all arguments as one string.
* print all arguments as seperate items.
* answer --> ex4.bash
* ### ex5.bash --> write a bash file  that after calling it will say Hello to the user. if no argument is entered it will say (hello guest).
* answer--> ex5.bash
* ### Note upto  here I got a basic understanding of Bash. I stop this tutorial for a period of time. and will continue later with probably deeper or more profesional tasks.-- regards--30 Jul 2025

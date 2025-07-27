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
* ### ex2.bash --> write a bash file to get the name of the user and say hello to him/her?
* page 23/69
* instead of the following two line of code:
*   - echo "please enter your name"
*   - read name
* we can write one line as below:
*   - read -p " please enter your name: " name
* 
* 

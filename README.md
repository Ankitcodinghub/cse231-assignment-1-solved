# cse231-assignment-1-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cse231-instructions-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128560&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE231 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
There should be ONLY ONE submission per group

Submit a .zip named RollNo1_RollNo2.zip file containing code and write-up.

Updates after the initial posting of assignment are highlighted in yellow.

1) A) Parent (P) is having ID &lt;PID&gt; B) ID of P’s Child is &lt;PID_of_Child&gt; The child should print two statements:

C) Child is having ID &lt;PID&gt;

D) My Parent ID is &lt;PID_of_Parent&gt;

Make use of wait() in such a manner that the order of the four statements A, B, C and D is: A, C, D, B. You are free to use any other relevant statement/printf as you desire and their order of execution does not matter.

2) Write a program to create two processes using vfork() system call in which the

child process will calculate the factorial of 4, and the parent process will calculate the Fibonacci series up to 16. Parent should wait for the child to

complete its working.

Clarification: For Fibonacci series, you have to calculate and print the first 16 elements of Fibonacci series

The following question is a bonus part:

Write a program to create two processes using vfork()/fork() system call in which the child process will calculate the factorial of 4, and parent process will calculate the Fibonacci series up to 16. The child should wait for the parent to complete its working.

Rubrics:

Student should have implemented following things:

● Program source code(s) with Makefile to compile.

● Write-up giving a brief description of how the program works (less than 1 page)

Q2 : You’re making a special unix system, and your project manager wants you to create three specific commands for c shell (c program that acts as a shell for your system) to be used in it.(50

1) word: It is a built-in (internal) command, Reads the number of words (assume word is a “space-separated” string) in a text file, and throws an error if the file does not exist.

Syntax: word [-option] [file_name]

It should additionally also cater 2 options:

● -n : ignores new line character

● -d : difference between the word sizes of two text files

Note: Only one of the options (-n or -d) can be used at a time with the word command.

2) dir: It creates a directory, and then changes the path to that directory. It is an external command, throw an error if that directory already exists.

Syntax: dir [-option] [dir_name]

It should additionally also cater 2 options:

● -r : removes if the directory already exists and create a new directory instead of throwing an error

It should additionally also cater 2 options:

● -d : display time described by STRING

Rubrics:

Student should have implemented following things:

● Program source code(s) with Makefile to compile.

● Write-up giving a brief description of how the program works (less than 1 page) ● Use C – libraries for implementing the shell commands.

● Use of exec(), fork(), wait()

● Error handling in terms of wrong command or wrong option or wrong argument

Create a bash script shell that acts like a math calculator. It should do these things:

1) Read a text file named “input.txt” that has two numbers and an operation in the format x y operation where x and y are numbers and the operation is the name of the command.

2) Calculate the result of that operation.

3) Save the result in a new text file named “output.txt” in the directory named “Result” (if the directory doesn’t exist in the current directory, make it).

There are only three operations:

1) “xor”: Get the xor of the two given numbers.

2) “product”: Get the product of the two given numbers.

3) “compare”: Get the bigger number from the two given numbers.

Rubrics:

Student should have implemented following things:

● Program source code(s) with Makefile to compile.

● Write-up giving a brief description of how the program works (less than 1 page)

● Read, write of text file through bash script only

● Creation of directory(if needed) through bash script only

Test Cases for the Assignment – 1

Q1) There is no test case for this question, the flow of expected output is mentioned in all three parts, and your solution should give the output in the same flow.

Q2)

Q3)

Input.txt

Output.txt

Input.txt

Output.txt

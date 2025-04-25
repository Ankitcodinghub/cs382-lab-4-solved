# cs382-lab-4-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs382-solved-6/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128073&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS382 Lab 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
            5/5 - (4 votes)    </div>
    </div>
&nbsp;

1 Task 1: Calculating Dot Product

The .data segment must be declared as follows:

where vec1 and vec2 are two vectors, and dot is where we store the dot product result. You must store the dot product into variable dot . There’s no need to use loops; you can just hard code the offsets for now. You can always assume the vector length is 3.

Requirements Note your code is a complete assembly program (not just a sequence of instructions). It should be able

to assemble, link, and execute without error and warnings. When executed, the program should finish without problems (also without any outputs);

If your code cannot assemble, you get no credit – this is the same as C programs that cannot be compiled;

MUL instruction can be used for multiplications;

Avoid using registers X29 and X30;

You must store the dot product result into the variable dot ;

You have to put comments on each line of instruction;

2 Task 2: Debugging Assembly Using gdb

To check if our programs are correct, we would have to rely on gdb (sorry, still not printf() yet!). A very comprehensive tutorial of using gdb to debug assembly programs is in Appendix B.3 of the textbook. Read through the section before you start this task.

In this task, you’d need to write a report on using gdb to debug task 1. You need to provide sufficient screenshots of gdb to show that your program is correct. Step into gdb and use commands to show that the result is correct.

Requirements

Simply one screenshot of showing the final result is not sufficient. For each step you took and command

you typed on gdb, you need a screenshot, and explain what you’re trying to accomplish at that step. For example, setting a break point needs one; stepping into an instruction needs one, and so on;

1

You must use the correct command to show directly that the dot-product calculation is correct and is stored

back to memory;

The screenshots must not be pictures taken from your phone or camera;

3 Grading

The lab will be graded based on a total of 10 points, 5 for task 1 and 5 for task 2. The following lists deductibles, and the lowest score is 0 – no negative scores:

Task 1:

• -3: the calculation result of dot-product is wrong;

• -3: the calculation result of dot-product is not in dot variable;

• -1: one or more instructions is missing comments;

• -1: the program has any type of output on terminal when executing;

• -1: no pledge and/or name. Task 2:

• -5: the report is not in PDF format;

• -2: the screenshots are not taken directly from the laptop;

• -2: missing screenshot and/or explanation of one or more steps in debugging; • -2: not showing the final value of dot-product calculation in gdb in memory;

• -1: no pledge and/or name in the report.

General deductions (only deduct once):

-10: the code in task 1

does not assemble, or the program terminates abnormally/unsuccessfully;

does not attempt the task;

is generated by a compiler;

cannot be explained clearly in person.

Attendance: check off at the end of the lab to get attendance credit.

2

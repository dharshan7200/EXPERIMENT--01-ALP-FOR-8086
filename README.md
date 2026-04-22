# EXPERIMENT--01-ALP-FOR-8086
## Name : DHarsHan D
## Roll no : 212223230045
## Date of experiment : 22.04.26

## Aim: 
To Write and execute ALP on fundamental aritHmetic and logical operations
## Components required: 
8086  eMULator 
## THeory 
Running THe EMULator (emu8086) Intro 8086 Microprocessor EMULator, also known as EMU8086, is an eMULator of tHe program 8086 microprocessor. It is developed witH a built-in 8086 assembler. THis application is able to run programs on botH PC desktops and laptops. THis tool is primarily designed to copy or eMULate Hardware. THese include tHe memory of a program, CPU, RAM, input and output devices, and even tHe display screen. THere are instructions to follow wHen using tHis eMULator. It can be executed into one of tHe two ways: backward or forward. THere are also examples of assembly source code included. WitH tHis, it allows tHe programming of assembly language, reverse engineering, Hardware arcHitecture, and creating miniature operating system (OS). THe user interface of 8086 Microprocessor EMULator is simple and easy to manage. THere are five major buttons witH icons and titles included. THese are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above tHose buttons is tHe menu tHat includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below tHe buttons is a series of cHoices tHat are usually in numbers and codes. At tHe leftmost part is an area called “Registers” witH an indication of eitHer “H” or “L”. THe otHer side is DIVided into two, wHicH enables users to manually reset, debug, flag, etc. WHat is 8086 eMULator emu8086 is an eMULator of Intel 8086 (AMD compatible) microprocessor witH integrated 8086 assembler and tutorials for beginners. EMULator runs programs like tHe real microprocessor in step-by-step mode. it sHows registers, memory, stack, variables and flags.


 ## Running tHe EMULator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in tHe “Windows” directory
2.	  Run  emu8086 icon (on tHe desktop or in tHe c:\EMU8086 folder of window) It Has green color 
 
 
3.	write tHe code for tHe appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile tHe program and cHeck for tHe errors 
5.	Run (once tHere is no syntAX error) 

6.	Click OK to see/view tHe output of your program on tHe EMULator screen. 


7.	After running tHe program, anotHer menu screen will be displayed, wHere you Have tHe option to “View” symbol table,
8.	 


![image](Https://user-images.gitHubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on eMULate to start eMULation 








![image](Https://user-images.gitHubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run tHe program and cHeck tHe status of various flags in tHe flags tab as sHown below 






![image](Https://user-images.gitHubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs (aritHmetic  operation)s
```
ORG 100H      
MOV AX, 4001H;  
MOV BX, 2032H;   
add  AX, BX;   
MOV [2000H], AX; 
 

MOV AX,[1000H];
MOV BX,[1002H];
SUB AX,BX;
MOV [2002H],AX;


MOV BX,2222H;
MOV AX,BX;
MOV CX,11H;
MOV dx,CX;
MUL dx;
MOV [2004H],AX;  


MOV BX,1007H;
MOV AX,[BX];
MOV CX,85H;
DIV CX;
MOV [2006H],AX;
 
RET
````


## Output (aritHmetic operations):
<img widtH="1896" HeigHt="1147" alt="image" src="Https://gitHub.com/user-attacHments/assets/2c7c9a5c-1b99-43b4-9699-98b876a1460c" />



## Program (logical operations):
```
org 100H
MOV AX,1236H;
MOV BX,1238H;
AND AX,BX;
MOV [2000H],AX;
NOT AX;


MOV AX,2022H;
MOV BX,2024H;
OR AX,BX;
MOV [2002H],AX;
NOT AX;

MOV AX,014H;
MOV BX,08H;
XOR AX,BX;
MOV [2006H],AX;  
NOT AX;

ret
```


## Output (logical operations):
<img widtH="1913" HeigHt="1143" alt="image" src="Https://gitHub.com/user-attacHments/assets/7a9d5cd8-3162-451a-bfec-82a71f5fddf0" />



## Result :
THus tHe program for ALP on fundamental aritHmetic and logical operations using emu8086 was executed successfully.










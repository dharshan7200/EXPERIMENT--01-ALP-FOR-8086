# EXPERIMENT--01-ALP-FOR-8086
## Name : Dharshan D
## Roll no : 212223230045
## Date of experiment : 22.04.26

## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  eMULator 
## Theory 
Running The EMULator (emu8086) Intro 8086 Microprocessor EMULator, also known as EMU8086, is an eMULator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or eMULate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this eMULator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor EMULator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “h” or “L”. The other side is DIVided into two, which enables users to manually reset, debug, flag, etc. What is 8086 eMULator emu8086 is an eMULator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. EMULator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the EMULator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntAX error) 

6.	Click OK to see/view the output of your program on the EMULator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on eMULate to start eMULation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs (arithmetic  operation)s
```
ORG 100h      
MOV AX, 4001h;  
MOV BX, 2032h;   
add  AX, BX;   
MOV [2000h], AX; 
 

MOV AX,[1000h];
MOV BX,[1002h];
SUB AX,BX;
MOV [2002h],AX;


MOV BX,2222h;
MOV AX,BX;
MOV CX,11h;
MOV dx,CX;
MUL dx;
MOV [2004h],AX;  


MOV BX,1007h;
MOV AX,[BX];
MOV CX,85h;
DIV CX;
MOV [2006h],AX;
 
RET
````


## Output (arithmetic operations):
<img width="1057" height="647" alt="image" src="https://github.com/user-attachments/assets/f4ab94fd-1640-4bab-b85d-9711f3f98e8c" />



## Program (logical operations):
```
org 100h
MOV AX,1236h;
MOV BX,1238h;
AND AX,BX;
MOV [2000h],AX;
NOT AX;


MOV AX,2022h;
MOV BX,2024h;
OR AX,BX;
MOV [2002h],AX;
NOT AX;

MOV AX,014h;
MOV BX,08h;
XOR AX,BX;
MOV [2006h],AX;  
NOT AX;

ret
```


## Output (logical operations):
<img width="1063" height="649" alt="image" src="https://github.com/user-attachments/assets/a3eac030-7e20-4480-9c0a-9daaf31c6988" />



## Result :
Thus the program for ALP on fundamental arithmetic and logical operations using emu8086 was executed successfully.










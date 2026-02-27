# EXPERIMENT 01 ALP FOR 8086

### Name : Pranav Bhargav M
### Register No. : 212224040239
### Department : CSE
### Date of experiment : 18-02-2026
 





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.	Write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

9.	Click on emulate to start emulation
    
![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)





## Programs for arithmetic  operations

## Addition 
```
ORG 100
MOV AL,11H;
MOV BL,20H;
ADD AL,BL;
MOV [6379H],AL;
RET
```
## Output  
 ![image](https://github.com/user-attachments/assets/251c5be6-bbfc-4ef4-b8e8-e3fffda2e3f9)

## Subtraction 
```
ORG 100
MOV AL,11H;
MOV BL,20H;
SUB AL,BL;
MOV [6379H],AL;
RET
```
## Output  
![image](https://github.com/user-attachments/assets/53fda628-6c2a-4e43-a211-bd1254679968)

## Multiplication 
```
ORG 100
MOV AL,11H;
MOV BL,20H;
MUL AL;
MOV [6379H],AL;
RET
```
## Output  
![image](https://github.com/user-attachments/assets/3cd125c3-3d8f-45e1-8e21-67814caef05b)


## Division 
```
ORG 100
MOV AL,11H;
MOV BL,20H;
DIV AL;
MOV [6379H],AL;
RET
```
## Output  
![image](https://github.com/user-attachments/assets/720b0dcc-075c-4213-87ce-327bc830f799)

## AND 
```
ORG 100H
MOV [SI],AX;
MOV AX,0A32H;
MOV BX,0B13H;
AND AX,BX;
RET
```
## Output
![image](https://github.com/user-attachments/assets/cba9d8d7-5bc8-4922-83c9-08c0cd884f42)

## OR
```
ORG 100H
MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
RET
```
## Output
![image](https://github.com/user-attachments/assets/367b4de0-0806-4fb1-8999-73fa43fa6b7d)

## NOT
```
ORG 100H
MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
RET
```
## Output
![image](https://github.com/user-attachments/assets/b4a64ee2-47e6-4294-8d94-fb14d6cda705)

## XOR
```
ORG 100H
MOV [SI+2],AX;
MOV AX,0A32H;
MOV BX,0B13H;
XOR AX,BX;
RET
```
## Output
![image](https://github.com/user-attachments/assets/86566c3a-f7e1-46ad-8e0f-a1392611405f)

## Result 
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.









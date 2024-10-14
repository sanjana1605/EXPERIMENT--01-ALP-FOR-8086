![Screenshot 2024-10-14 141530](https://github.com/user-attachments/assets/1bc59c37-981b-47eb-a7a4-5ccc5fe24b7d)# EXPERIMENT--01-ALP-FOR-8086
Name : SANJANA SRI N
Roll no 
Date of experiment :





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
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

## Addition  of 8 bit ALP 
MOV AL,74H
MOV BL,69H
ADD AL,BL
HLT



## Output ![Screenshot 2024-10-14 140726](https://github.com/user-attachments/assets/fe7e0978-87f8-4972-bdc6-741aa70112a3)
 
 
## Subtraction   of 8 bit numbers  ALP 
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT


 
## Output  
![Screenshot 2024-10-14 140926](https://github.com/user-attachments/assets/a02dfe04-f2d5-4e22-a9bb-c72f0a1cfdd4)

## Multiplication alp 
MOV AL,75H
MOV BL,32H
MUL BL
HLT

## Output 
![Screenshot 2024-10-14 141324](https://github.com/user-attachments/assets/c6f05378-04a6-46ab-b558-38abb8b62b14)



## Division alp 
MOV AL,68H
MOV BL,18H
DIV BL
HLT

## Output  
![Screenshot 2024-10-14 141425](https://github.com/user-attachments/assets/2e8043d2-715e-4096-a224-b172c79f78af)


## and alp
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT

## Output
![Screenshot 2024-10-14 141530](https://github.com/user-attachments/assets/28f7897f-0281-4faf-959b-868546f0df83)


## or alp
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT

## Output
![Screenshot 2024-10-14 141625](https://github.com/user-attachments/assets/48fd105a-7446-4be0-9232-505ba8b249ee)

## not alp
MOV AL,65H
NOT AL
HLT

## Output
![Screenshot 2024-10-14 141733](https://github.com/user-attachments/assets/1275c63e-9a8d-4b1f-9d2a-1d93ee3b2ae3)

## xor alp
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT

## Output
![Screenshot 2024-10-14 141825](https://github.com/user-attachments/assets/0c1362c7-bc6e-4414-b4c5-57866b4566c1)



## Result :
Thus to Write and execute ALP on fundamental arithmetic and logical operations are verified
successfully.

 









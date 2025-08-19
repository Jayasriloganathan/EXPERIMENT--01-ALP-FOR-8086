# EXPERIMENT--01-ALP-FOR-8086
```
Name :Jayasri L
Roll no : 212224040136
Date of experiment : 19.08.2025
```

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

## program code:

```
org 100h
mov ax,1532h
mov bx,1286h 
mov cx,1345h
mov dx,1325h

add ax,bx  
mov [1000h],ax 

sub cx,dx
mov [1002h],cx

mul bx
mov [1004h],bx

div dx
mov [1006h],dx                
ret

```

## Output


<img width="1795" height="1013" alt="Screenshot 2025-08-19 091822" src="https://github.com/user-attachments/assets/31ebec37-f789-4a31-a0b6-b38fdcfab810" />



## Result :
```
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
```

## Programs for logic operations

## Program code:

```
org 100h

mov ax,2345h
mov bx,1111h
mov cx,5678h
mov dx,3686h

and ax,bx
mov [1000h],ax

or cx,dx
mov[1002h],cx

xor bx,dx
mov [1004h],bx

not dx
mov [1006h],dx
ret

```

## Output

<img width="1775" height="1011" alt="Screenshot 2025-08-19 091036" src="https://github.com/user-attachments/assets/9f57f1d0-a3ce-48ea-8336-28d779ced5fc" />


## Result
```
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.


```


 









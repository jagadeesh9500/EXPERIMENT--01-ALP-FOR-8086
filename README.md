# EXPERIMENT 01 ALP FOR 8086
Name : jagadeesh P

Roll no : 212223230083





## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
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

```

org 100h

mov ax,0abcdh
mov bx,2347h
add ax,bx

ret
```






## Output 
![add](https://github.com/user-attachments/assets/aee9d94a-768e-41d6-a3ae-5f93914bcbef)

 
## Subtraction   of 8 bit numbers  ALP 

```
org 100h

mov ax,[2345h]
mov bx,[1563h]
sub ax,bx

ret
```




 
## Output  
![sub](https://github.com/user-attachments/assets/234cb4bf-fe7c-4383-9e0f-b2c39af0a822)

## Multiplication alp 
 
```
org 100h  

mov cx,2345h
mov bx,1563h
mov ax,bx 
mov dx,cx 

mul dx   

ret

```














 ## Output  
![multi](https://github.com/user-attachments/assets/1e690ebb-5df7-4c35-9220-108ad7f53e86)


## Division alp 
```
org 100h  

mov bx,5005h
mov ax,[bx]
mov cx,05h
div cx 

ret
```
## Output  
![div](https://github.com/user-attachments/assets/c3b7ee06-5455-46f1-8f91-1da5e2c6f263)

## Programs for logical  operations: 

## AND:
```
org 100h

mov ax,1234h 
mov bx,3456h
AND ax,bx

ret
```
## Output 
![and](https://github.com/user-attachments/assets/273dc49b-a45f-4141-b34f-0547d2b7d400)


## OR :
```
org 100h

mov ax,1234h 
mov bx,3456h
or ax,bx

ret
```
## Output 
![or](https://github.com/user-attachments/assets/7a97c236-fdbb-4477-bd13-9b8d3725a8ac)


## NOT :
```
org 100h

mov ax,1234h 
NOT ax,bx

ret
```
## Output
![not](https://github.com/user-attachments/assets/0d4f0378-a056-40ff-8f46-3d1850d75231)


## XOR :
```
org 100h

mov ax,1234h 
mov bx,3456h
XOR ax,bx

ret
```
## Output 
![xor](https://github.com/user-attachments/assets/9425d74c-33ab-4021-831d-a978dae434ce)


## Result :
The ALP on fundamental arithmetic and logical operations is executed successfully.
 
 









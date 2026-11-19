# EXPERIMENT--01-ALP-FOR-8086
### Name :PRIYANKA P
### Roll no : 212224230212
### Date of experiment : 19.11.2026


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
```
MOV AX,1234H
MOV BX,2345H
ADD AX,BX
HLT
```



## Output  
<img width="1919" height="1009" alt="image" src="https://github.com/user-attachments/assets/360e7a00-35f8-47c0-bb51-bf822847ec64" />


## Subtraction   of 8 bit numbers  ALP 
```
MOV AX,5436H
MOV BX,8764H
SUB AX,BX
HLT
```
 
## Output  

<img width="1717" height="947" alt="image" src="https://github.com/user-attachments/assets/a2eb02ca-cb19-4848-a4b4-28a9753bcf34" />

## Multiplication alp 
```
MOV AX,356CH
MOV BX,467DH
MUL BX
HLT
```
 ## Output  
<img width="1786" height="977" alt="image" src="https://github.com/user-attachments/assets/73daab57-00e6-4c54-a4ea-3352e7d29cce" />


## Division alp 
```
MOV AX,5467H
MOV BX,2345H
DIV BX
HLT
```

## Output  
<img width="1810" height="992" alt="image" src="https://github.com/user-attachments/assets/5a74f47f-8ff7-4391-be83-4ea70c1e0d71" />

## Programs for arithmetic  operations
## AND of 16 bit numbers ALP
```
MOV BX,3527H
MOV CX,2968H
AND BX,CX
RET
```

## OUTPUT
<img width="978" height="536" alt="image" src="https://github.com/user-attachments/assets/c6a070e9-ad00-4d0a-a1a5-b5e6809619f0" />

## NAND of 16 bit numbers ALP
```
MOV BX,3527H
MOV CX,2968H
AND BX,CX
NOT BX
RET
```

## OUTPUT
<img width="971" height="537" alt="image" src="https://github.com/user-attachments/assets/88956bb1-7d3b-40b1-868e-344b1b40f31b" />

## OR of 16 bit numbers ALP
```
MOV BX,3527H
MOV CX,2968H
OR BX,CX 
RET
```

## OUTPUT
<img width="962" height="536" alt="image" src="https://github.com/user-attachments/assets/5f0d4f51-fd23-46a0-854f-01e7f52b8eab" />

## NOR of 16 bit numbers ALP
```
MOV BX,3527H
MOV CX,2968H
OR BX,CX
NOT BX
RET
```

## OUTPUT
<img width="965" height="537" alt="image" src="https://github.com/user-attachments/assets/261fc63b-fa1d-4cbb-b1c9-664481a8da14" />

## XOR of 16 bit numbers ALP
```
MOV BX,3527H
MOV CX,2968H
XOR BX,CX
RET
```

## OUTPUT
<img width="977" height="540" alt="image" src="https://github.com/user-attachments/assets/551cc39d-4863-47fb-8c0c-76ba5558794c" />

## XNOR of 16 bit numbers ALP
```
MOV BX,3527H
MOV CX,2968H
XOR BX,CX
NOT BX
RET
```

## OUTPUT
<img width="952" height="523" alt="image" src="https://github.com/user-attachments/assets/393bff2a-c36d-4300-aeff-1681f9c8f567" />

## NOT of 16 bit numbers ALP
```
MOV AX,276DH
NOT AX
RET
```

## OUTPUT
<img width="950" height="521" alt="image" src="https://github.com/user-attachments/assets/0225709a-668e-4079-b882-b2806f991e15" />

## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.

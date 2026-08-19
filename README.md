# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE
- 

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```ORG 0000H
MOV R0,#50H
MOV A,@R0 
MOV B,@R0 
MUL AB
INC R0 
MOV @R0,A
END









```

## OUTPUT
<img width="1600" height="839" alt="WhatsApp Image 2026-07-31 at 2 19 03 PM" src="https://github.com/user-attachments/assets/378f4b1f-3e00-46a3-ab27-ab2a5ad8f356" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```

ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END






```


## OUTPUT
<img width="1600" height="838" alt="WhatsApp Image 2026-07-31 at 2 19 04 PM" src="https://github.com/user-attachments/assets/e10268df-9ed8-4fda-a443-6632b0fd1f71" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.



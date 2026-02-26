# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
INC R0
MOV @R0,A
END


```
### CALCULATION 

<img width="577" height="1280" alt="image" src="https://github.com/user-attachments/assets/fc9c872b-a403-4c1e-91de-cfd510562c0d" />

## OUTPUT

<img width="1047" height="630" alt="image" src="https://github.com/user-attachments/assets/ca3d6f60-a833-4c8c-a9c8-5d7da89a902e" />

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
MOV @R0,A
END

```

### CALCULATION 

<img width="577" height="1280" alt="image" src="https://github.com/user-attachments/assets/adc36c55-969a-4909-b405-30bb748b0510" />

## OUTPUT

<img width="1048" height="752" alt="image" src="https://github.com/user-attachments/assets/ba55b55a-c94c-469f-b58d-88bcc386f30a" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.



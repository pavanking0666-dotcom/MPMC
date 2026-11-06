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
ORG 000H
MOV RO,#50H
MOV A,@RO
MUL AB
INC RO
MOV @RO,A
END









```

## OUTPUT
<img width="1600" height="856" alt="image" src="https://github.com/user-attachments/assets/e4663bb4-3141-4da1-8318-64755b2fd899" />


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
MOV A,@RO
MOV B,A
MUL AB
MOV B,@RO
MUL AB
INC RO
MOV @RO,A
INC RO
MOV @RO
MOV @RO,B
END








```


## OUTPUT
<img width="1600" height="850" alt="image" src="https://github.com/user-attachments/assets/2883af52-0a0e-4e73-9341-730fd17d16dd" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.



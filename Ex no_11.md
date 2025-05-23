# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:
## Aim:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm:
1. Start. 
2. Declare a integer variable 
3. Define a function named dectobin. 
4. Return the integer. 
5. Read the value using scanf. 
6. Convert decimal to binary value. 
7. Print the dectobin 
8. End.  

## Program:
```
#include<stdio.h> 
Int dectobin(int d)
{ 
int bin =0,base=1,rem; 
  while(d>0) 
  { 
    rem=d%2; 
    bin=bin+rem*base; 
    d=d/2; 
    base=base*10; 
  } 
printf(" = %d in binary",bin); 
return 0; 
} 
int main() 
{ 
int dec; 
scanf("%d",&dec); 
printf("%d in decimal",dec); 
dectobin(dec); 
return 0; 
}
```

## Output:
![Screenshot 2025-05-06 195511](https://github.com/user-attachments/assets/08cbc1a3-6bed-43e3-be77-bba548a7257d)

## Result:
Thus the program was executed and the output was verified successfully.

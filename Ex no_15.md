# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:
## Aim:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm:
1. Start. 
2. Declare a array size value of type int. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Initialize array elements. 
6. Replace all even elements to E 
7. End.   

## Program:
```
#include<stdio.h>
int main()
{
    int a,i;
     scanf("%d",&a);
    int b[a];
    for(i=0;i<a;i++)
    {
        scanf("%d",&b[i]);
    }
     for(i=0;i<a;i++)
    {
        if(b[i]%2==0)
        printf("E ");
        else
        printf("%d ",b[i]);
    }    
} 
```

## Output:
![Screenshot_6-5-2025_201847_training saveetha in](https://github.com/user-attachments/assets/9dc45814-5722-4aab-9c6e-1bc41edabb39)

## Result:
Thus the program was executed and the output was verified successfully.

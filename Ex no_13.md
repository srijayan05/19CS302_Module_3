# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## Aim:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm:
1. Start. 
2. Define a variables i,j,n,a. 
3. Write program to find n x n matrix. 
4. Read the value using scanf. 
5. Ask the user to make an input 
6. Print out the answer. 
7. End.  

## Program:
```
#include <stdio.h>

int main()
{
    int n;
    int i, j;
    scanf("%d", &n);
    int arr[n][n]; 
    for(i = 0; i < n; i++)
{
        for(j = 0; j < n; j++)
       {
            scanf("%d", &arr[i][j]);
        }
    }
    for(i = 0; i < n; i++)
  {
        for(j = 0; j < n; j++)
        {
            if(arr[i][j] % 2 != 0)
            {
                printf("%d ", arr[i][j]);
            }
        }
    }
    printf("\n");
    return 0;
}
```
## Output:
![Screenshot_6-5-2025_20104_training saveetha in](https://github.com/user-attachments/assets/e795d09e-a6f2-4897-ab9a-2a213294ed03)


## Result:
Thus the program was executed and the output was verified successfully.

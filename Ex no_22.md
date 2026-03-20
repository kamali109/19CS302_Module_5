# EX 22 C program to count total number of even elements in an array using calloc().

## AIM:
To write a C program to count total number of even elements in an array using calloc().

## Algorithm
```
.Start the program and declare a file pointer.

2.Use fopen() in write mode to create and open the file "Hospital.txt".

3.Check if the file was created and opened successfully and display a message.

4.Close the file using fclose() after confirming successful opening.

5.Display a message indicating the file was closed successfully.
```
## Program:
```
/*
C program to count total number of even elements in an array using calloc().
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include <stdio.h> 
int main() { 
    char str1[100], str2[100]; 
    int i = 0, flag = 0; 
    scanf("%s", str1); 
    scanf("%s", str2); 
    while (str1[i] != '\0' || str2[i] != '\0') { 
        if (str1[i] != str2[i]) { 
            flag = 1; 
            break; 
        } 
        i++;    }    
 if (flag == 0)         
printf("Strings are equal.\n"); 
 else 
        printf("Strings are not equal.\n"); 
    return 0; 
} 
```

## Output:

<img width="624" height="140" alt="image" src="https://github.com/user-attachments/assets/1ac7fb56-4aed-4561-9c78-043c0cbfd158" />


## Result:
Thus the program was executed and the output was verified successfully.

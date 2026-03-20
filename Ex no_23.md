# EX 23 C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## AIM:
To write a C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## Algorithm
```
1.Start the program and declare a file pointer.

2.Use fopen() in write mode to create and open the file "Hospital.txt".

3.Check if the file was created and opened successfully and display a message.

4.Close the file using fclose() after confirming successful opening.

5.Display a message indicating the file was closed successfully.
```

## Program:
```
/*
C program to store and display the name, id, age and salary of an employee using structure(using array of structure).
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include<stdio.h> 
#include<string.h> 
int main() 
{ 
int i,count=0,len; 
char str[100],val[100];  
scanf("%s %s",str,val);  
len=strlen(str);  
for(i=0;i<len;i++){ 
if(str[i]==val[0])  
count++; 
}printf("%d",count);}
```

## Output:
<img width="178" height="191" alt="image" src="https://github.com/user-attachments/assets/af84878c-5485-4f1b-ae18-9069646569c2" />

## Result:
Thus the program was executed and the output was verified successfully.

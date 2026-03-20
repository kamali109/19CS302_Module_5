# EX 25 C program to check whether a given character is a vowel or consonant using pointer

## AIM:
To write a C program to check whether a given character is a vowel or consonant using pointer.

## Program:
```
/*
C program to check whether a given character is a vowel or consonant using pointer
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include <stdio.h>
int main() {
 char str[100];
 char *p;
 int vowels = 0, consonants = 0;
 scanf(" %[^\n]", str); 
 p = str; 
 while (*p != '\0') {
 if ((*p >= 'A' && *p <= 'Z') || (*p >= 'a' && *p <= 'z')) {
 char ch = (*p >= 'A' && *p <= 'Z') ? *p + 32 : *p;
 if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') {
 vowels++;
 } else {
 consonants++;
 }
 }
 p++;
 }
 printf("Vowels: %d\n", vowels);
 printf("Consonants: %d\n", consonants);
 return 0;
}
```

## Output:
<img width="468" height="192" alt="image" src="https://github.com/user-attachments/assets/f264f5c1-bcad-4328-926d-cd05990dd365" />



## Result:
Thus the program was executed and the output was verified successfully.

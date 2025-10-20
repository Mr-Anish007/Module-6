# Program-6-a
## C-Module 6
## EX_NO-06)a)-Pointers
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
Write a C program to find character 'R' is vowel or consonant using pointer.
## ALGORITHM:
1. Start the program.
2. Declare a character variable to store the input character.
3. Read a character from the user using scanf.
4. Declare a character pointer and assign it the address of the input character.
5. Check if the value pointed to by the pointer is a vowel (A, E, I, O, U in uppercase or lowercase):

    a. If true, print "<character> is vowel."

   b. Otherwise, print "<character> is consonant."

6. End the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    char *p1=&ch;
    if(*p1=='A'||*p1=='a'||*p1=='E'||*p1=='e'||*p1=='i'||*p1=='I'||*p1=='o'||*p1=='O'||*p1=='U'||*p1=='u')
    printf("%c is vowel.",*p1);
    else 
    printf("%c is consonant.",*p1);
}
```
## OUTPUT:
<img width="842" height="287" alt="image" src="https://github.com/user-attachments/assets/aba2fbe3-e79f-45ae-aec1-ea8034a8d7af" />

## RESULT:
Thus the program to find character 'R' is vowel or consonant using pointer has been executed successfully

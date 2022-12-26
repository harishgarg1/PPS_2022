ed file with 18 additions and 0 deletions.
 18  
2221033/prog16.md
@@ -0,0 +1,18 @@
## Program 16 Write a program to get character input from user
```
#include<stdio.h>
int main()
{
char a;
printf("Please enter a character\n");
scanf("%c", &a);
printf("The character you entered is %c",a);
return 0;
}
```
**Output**
```
Please enter a character
a
The character you entered is a
```

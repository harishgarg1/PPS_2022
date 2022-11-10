## Program 13: Write a program to show the use of break statement
```
#include <stdio.h>
int main() 
{
int i = 0;
while (i < 10) 
{
if (i == 8) 
{
break;
}
printf("%d\n", i);
i++;
} 
return 0;
}
```
**Output**
```
0
1
2
3
4
5
6
7
```

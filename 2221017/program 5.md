## Program 5 : Write a program using conditional operators

```
#include<stdio.h>
int main()
{
int T=90,P=90,c;
c=(T>80&&P>80)?1000:(P>80)?500:0;
printf("%d",c);
return 0;
}
```
**Output : 1000**

http://wbzyl.inf.ug.edu.pl/c/elementarz-3

ZADANIE 1


```c
#include <stdio.h>
int main()
{
    int c;
    while ((c = getchar()) != EOF)
        if (c == '\t')
         printf("\\t");
        else if (c == '\\')
         printf("\\\\");
        else
         putchar(c);
    return 0;
}

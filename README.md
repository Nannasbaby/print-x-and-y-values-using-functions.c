#include <stdio.h>
int y=90;
void f1(int x)
{
    printf("%d\t%d",x,y);
}
int main()
{
    int x=10;
    f1(x);
}

# code-hacks
#include <stdio.h>
int fact(int);

int main()
{
    int x,a;
    scanf("%d",&x);
    a=fact(x);
    printf("%d",a);
    return 0;
}
int fact(int n)
{
    int i,s=1;
    for(i=n;i>0;i--)
    {
        s=s*i;
    }
    return s;
}

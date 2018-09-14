# Greater-of-three-numbers
#include<stdio.h>
#include<conio.h>
int main()
{clrscr();
int a,b,c;
printf("Enter !st Number:");
scanf("%d", &a);
printf("Enter 2nd Number:");
scanf("%d", &b);
printf("Enter 3rd number:");
scanf("%d", &c);
if(a>=b && a>=c)
{
printf("a is bigger of all three");
}
else if(b>=c && b>=a)
{
printf("b is bigger of all three");
}
else if(c>=a && c>=b)
{
printf("c is bigger of all three");
}
getch();
return 0;
}

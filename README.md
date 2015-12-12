#include<stdio.h>
#include<conio.h>
void main()
{
  int n1,n2,lcm,gcd,num,de,r;
  clrscr();
  printf("enter the two numbers");
  scanf("%d%d",&n1,&n2);
  if(n1>n2)
  {
      num=n1;
      de=n2;
  }  
  else
  {
     num=n2;
     de=n1;
  }
  r=num%de;
  while(re!=0)
  {
    
   num = de;
   de = r;
    r = numr % de;
}
gcd = de;
lcm = (n1 * n2 ) / gcd;

printf("GCD of %d and %d =%d\n" , n1, n2, gcd);
printf(" LCM of %d and %d= %d\n" , n1, n2, lcm);
getch();
}

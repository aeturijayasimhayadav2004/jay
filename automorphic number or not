#include<stdio.h>
#include<conio.h>

int main()
{
 long int number, square, flag=1;
 clrscr();
 printf("Enter integer number:\n");
 scanf("%ld", &number);
 square = number * number;
 while(number!=0)
 {
  if(square%10 != number%10)
  {
   flag=0;
   break;
  }
  number = number/10;
  square = square/10;
 }
 if(flag==1)
 {
  printf("AUTOMORPHIC");
 }
 else
 {
  printf("NOT AUTOMORPHIC");
 }
 getch();
 return 0;
}

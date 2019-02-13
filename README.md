# My-codes
#include<stdio.h>
#include<string.h>

void wiper1();
void delay();

int main()
{

    int eng;

    printf("enter the engine state");
    scanf("%d",&eng);

    if(eng== 1){
             printf("grgr");
         wiper1();

    }

    else{
        printf("the engine is in off state\n");
}
}

void wiper1()
{

    int n;
    n=rand()%5+1;

  switch(n){
  case 1:
        delay(1000000);
        printf("//////////\n");
       ;
        break;
  case 2:
        delay(10000);
        printf("$$$$$$$$$\n");

        break;
  case 3:
        delay(1000);
        printf("*********\n");

        break;
  case 4:
        delay(1000);
         printf("@@@@@@@@@@\n");

        break;
  case 5:
        delay(100);
         printf("&&&&&&&&&&&\n");

        break;

  default :
         printf("enter the correct number");
  }
    }


    }

  void delay(int x)
{
    int i;
   for(int i=0;i<x;x++);


   }









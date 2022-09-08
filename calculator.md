```c
#include <stdio.h>
void menu(){
    printf("* * * * * * * * * * * * * * * * * * * * *\n");
    printf("*\tS.NO\t*\tOperator\t*\n");
    printf("* * * * * * * * * * * * * * * * * * * * *\n");
    printf("*\t1.\t*\t(+)             *\n");
    printf("*\t2.\t*\t(-)             *\n");
    printf("*\t3.\t*\t(*)             *\n");
    printf("*\t4.\t*\t(/)             *\n");
    printf("* * * * * * * * * * * * * * * * * * * * *\n");
}
int main()
{
   menu();
    char Operator;
    int num1,num2,result;
    printf("Enter your choice:");
    scanf("%c", &Operator);
    printf("Enter Operand num1 : ");
    scanf("%d", &num1);
    printf("Enter Operand num2 : ");
    scanf("%d", &num2);
    switch(Operator){
        case '+': result = num1 + num2;
           break;
        case '-': result = num1 - num2;
           break;
        case '*': result = num1 * num2;
           break;
        case '/': result = num1 / num2;
           break;
        default: printf("\n Invalid Operator ");
   
   }
   printf("The value = %d",result);
   return 0;
}

##OUTPUT


* * * * * * * * * * * * * * * * * * * * *
*       S.NO    *       Operator        *
* * * * * * * * * * * * * * * * * * * * *
*       1.      *       (+)             *
*       2.      *       (-)             *
*       3.      *       (*)             *
*       4.      *       (/)             *
* * * * * * * * * * * * * * * * * * * * *
Enter your choice:*
Enter Operand num1 : 2
Enter Operand num2 : 3
The value = 6
```

# Quiz-using-Switch


#include<stdio.h>
int main ()
{
int father,year;

printf(" (A) Who is known as the father of computers?");
printf("\n\n (1) Bill Gates ");
printf("\n (2) Charles Babbage");
printf("\n (3) Mark Zuckerberg");
printf ("\n\n\n Type here - ");
scanf("%d",&father);

printf("\n\n\n (B) When was the first computer invented?");
printf("\n\n (1) 1945");
printf("\n (2) 1943");
printf("\n (3) 1948");
printf("\n\n\n Type here - ");
scanf("%d",&year);


switch (father)
{
case 1 :


printf("\n (A) Wrong answer\n");
             switch (year)
           {
             case 1 :
             printf("\n (B) Wrong Answer");
            break;
            case 2 :
            printf("\n (B) Right Answer"); 
            break;
            case 3:
            printf("\n (B) Wrong Answer");
            break;
            default:
            printf("\n (B) Wrong Input");
           }
break;



case 2 :
printf("\n (A) Right answer\n");
           switch (year)
        {
            case 1 :
            printf("\n (B) Wrong Answer");
            break;
            case 2 :
            printf("\n (B) Right Answer"); 
            break;
            case 3:
            printf("\n (B) Wrong Answer");
            break;
            default:
            printf("\n (B) Wrong Input");
        }
           
break;



case 3 :
printf("\n (A) Wrong Answer \n");
         switch (year)
        {
            case 1 :
            printf("\n (B) Wrong Answer");
            break;
            case 2 :
            printf("\n (B) Right Answer"); 
            break;
            case 3:
            printf("\n (B) Wrong Answer");
            break;
            default:
            printf("\n (B) Wrong Input");
        }
break;

default:
        
printf("\n (A) Wrong Input\n ");
}
return 0;
}

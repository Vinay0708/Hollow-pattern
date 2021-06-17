# Hollow-pattern
#include<stdio.h>
int main()
{   
    int row,star,space,n;
    printf("Enter number of rows for print these pattern:");
    scanf("%d",&n);
    for(row=1;row<=n;row++)
    {
        if(row==1|| row==n)
        {
            for(star=1;star<=row;star++)
              printf("*");
            printf("\n");
        }
        else
       {
          printf("*");
        for(space=1;space<=row-2;space++)
        printf(" ");
        printf("*");
        printf("\n");
       }
    }
    return 0;
}
       

# pattern.c
write a program 111 22 3?
#include <stdio.h>

int main()
{
    int i,j,num;
    scanf("%d",&num);
    for(i=0;i<num;i++){
        for(j=0;j<i;j++){
            printf(" ");
        }
        for(j=i;j<num;j++){
            printf("%d",i+1);
        }
        printf("\n");
    }
}

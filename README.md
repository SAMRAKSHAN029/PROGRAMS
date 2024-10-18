
#include <stdio.h>
int main() {
int regno;
int fee;
float percentage;
char name[100];
char dept[100];
printf("ENTER YOUR REG NUM; ");
scanf("%d",&regno);
printf("ENTER YOUR PERCENTAGE; ");
scanf("%f",&percentage);
printf("ENTER Your name; ");
scanf("%s",name);
printf("ENTER Your dept; ");
scanf("%s",dept);
printf("ENTER YOUR fee; ");
scanf("%d",&fee);
printf("\nNAME: %s",name);
printf("\nREG NUM: %d",regno);
printf("\nDEPARTMENT: %s",dept);
printf("\nPERCENTAGE: %.2f",percentage);
printf("\nFEE : %d",fee);
}






# vaccination-slot-booking
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
{
    int age,dose;
    char name[30],sex[10],area[50],vaccine[50];
    printf("enter your age : ");
    scanf("%d",&age);
    if(age>=18){
    if(age>=18){
    printf("please enter your details\n");
    printf("enter your name : \n");
    scanf("%s",name);
    printf("enter your gender : \n");
    scanf("%s",sex);
    printf("enter you area name : \n");
    scanf("%s",area);
    printf("enter your vaccine name : \n");
    scanf("%s",vaccine);
    printf("enter your dose number : \n");
    scanf("%d",&dose);
    }
    else{
    printf("you are not eligible for vaccination \n");
    }
    int number,number2;
    srand(time(0));
    number=rand()%30+1;
    number2=rand()%7;
    if(number2==0){
        number2=2;
    }
    printf("##########################################################\n");
    printf("               VACCINATION  TICKET                      \n");
    printf("                                    DATE : %d/%d/2022   \n",number,number2);
    printf("                                                        \n");
    printf("   Your name               : %s                         \n",name);
    printf("                                                        \n");
    printf("   Your gender             : %s                         \n",sex);
    printf("                                                        \n");
    printf("   Your area               : %s                         \n",area);
    printf("                                                        \n");
    printf("   Your vaccine name       : %s                         \n",vaccine);
    printf("                                                        \n");
    printf("   Your dose number        : %d                         \n",dose);
    printf("                                                        \n");
    printf("   Your vaccination center : %s government hospital     \n",area );
    printf("                                                        \n");
    printf("                                                        \n");
    printf("  Precautions :                                         \n");
    printf("  * Use sanitizer and mask *                            \n");
    printf("  * Without mask , no entry to vaccination center *     \n");
    printf("  * Stay home , Stay safe *                             \n");
    printf("##########################################################\n");
}
if(age<18){
    printf("you are a small kid please go aside and drink some cow milk");
}
    return 0;
}

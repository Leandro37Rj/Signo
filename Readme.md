#include<stdio.h>

int main()
{
        
        int dia;
        int mês;
    
        printf("       ### Descubra seu Signo ###\n        ♑♐♏♎♍♌♋♊♉♒♈♓ ");
        printf("\n\n\n  ## Digite o Dia do seu Aniversário ##                  ");
         scanf("%i", &dia);
        printf("\n\n  ## Digite o mês ## : ");
         scanf("%i", &mês);
         
    
    if ( dia >= 21 && dia <=30 && mês == 1 || dia >= 1 && dia <= 18 && mês == 2){
        printf("\n      ♒ Aquário ♒\n  ");
    }
    
    if ( dia >= 19 && dia <= 28 && mês == 2 || dia >= 1 && dia <= 20 && mês == 3){
        printf("\n      ♓ Peixes ♓ \n   ");
    } 

     if ( dia >= 21 && dia <= 30 && mês == 3 || dia >= 1 && dia <= 20 && mês == 4){
        printf("\n     ♈ Áries ♈\n    ");
    }

     if ( dia >= 21 && dia <= 30 && mês == 4 || dia >= 1 && dia <= 20 && mês == 5){
        printf("\n     ♉ Touro ♉\n     ");
    }

     if ( dia >= 21 && dia <= 30 && mês == 5 || dia >= 1 && dia <= 20 && mês == 6){
        printf("\n    ♊ gêmeos ♊\n      ");
    }
    
     if ( dia >= 21 && dia <= 30 && mês == 6 || dia >= 1 && dia <= 22 && mês == 7){
        printf("\n     ♋ câncer ♋\n      ");
    }

     if ( dia >= 23 && dia <= 30 && mês == 7 || dia >= 1 && dia <= 22 && mês == 8){
        printf("\n     ♌ Leão ♌\n         ");
    }

     if ( dia >= 23 && dia <= 30 && mês == 8 || dia >= 1 && dia <= 22 && mês == 9){
         printf("\n     ♍ Virgem ♍\n       ");
    }

     if ( dia >= 23 && dia <= 30 && mês == 9 || dia >= 1 && dia <= 22 && mês == 10){
        printf("\n     ♎ Libra ♎\n         ");
    }

     if ( dia >= 23 && dia <= 30 && mês == 10 || dia >= 1 && dia <= 21 && mês == 11){
        printf("\n     ♏ Escorpião ♏\n      ");
    } 
   
     if ( dia >= 22 && dia <= 30 && mês == 11 || dia >= 1 && dia <= 21 && mês == 12){
        printf("\n     ♐ Sagitário ♐\n       ");
    }
   
     if ( dia >= 22 && dia <= 30 && mês == 12 || dia >= 1 && dia <= 20 && mês == 1){
        printf("\n      ♑ Capricórnio ♑\n     ");
    } 
   
     










} 

#include <stdio.h>
#include <stdlib.h>


int tela(){
 int opcao;
    system("cls");
    
    printf("\n--------------Menu------------\n");
    
    printf("\n1-opcao\n");
    
    printf("\n2-sair\n");
    
    printf("\n------------------------------\n");
    
     printf("Digite sua opcao:");
     
    scanf("%d", &opcao);
    
   return opcao;
}





int main(){

int opcao;

opcao  = tela();

switch (opcao)
{
case 1:
    printf("sua opcao é 1");
    break;
    case 2:
    printf("sua opcao é 2");
    return 0;
    break;


default:
   
    printf("errado!!!!");
   
    break;
}





    return 0;
}


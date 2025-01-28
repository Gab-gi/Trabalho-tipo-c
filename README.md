/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>

int main()

   int idade, matricula;
   float altura;
   char nome[50];
   
   printf ("Digite sua idade:/n");
   scanf ( "%d", &idade);
   
   printf ("Digite sua altura:/n");
   scanf ("%f", &altura);
   
   printf ("Digite seu nome:/n");
   scanf ("%s", &nome);
   
   printf ("Digite sua matricula");
   scanf ("%d", &matricula);
  
  printf ("Nome do aluno: %s - Matricula: %d" ,nome, matricula);
  printf ("Idade: %d - Altura: %f", idade, altura);
    return 0;
}

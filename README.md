# aula-logica-emprestimo
#include<stdio.h>
int main ()
{
int sal, e , score;
printf("Qual sua faixa salarial?");
scanf("%i",&sal);
printf("Qual seu tempo de exp?");
scanf("%i",&e);
printf("Qual o seu score?");
scanf("%i",&score);
//salario>2000 OU experiencia>5 anos
//E o score NAO pode ser abaixo de 300
if((sal>2000||e>5)&& !(score<300))
{
    printf("EMPRESTIMO CONCEDIDO!");

}
else
{
    printf("EMPRESTIMO NEGADO!");
}
}




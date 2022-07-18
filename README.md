# Quantidade-negativos

Exercício 5: Quantidade negativos
Gabarito do Exercício 5
Exercício 5: Ler 10 valores e escrever quantos desses valores lidos são NEGATIVOS.

OPÇÃO COM PARA

programa

{

   funcao inicio(){

      inteiro valor, soma

      valor = 0

      soma = 0

      para(inteiro contagem = 1; contagem <= 10, contagem++) {

         leia (valor)

         se (valor < 0){

            soma = soma + 1
         }

      }

      escreva("A quantidade de negativos é: ", soma)

   }

}

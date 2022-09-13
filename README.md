# visualgvetordoisint
Crie um algoritmo onde o usuário fornece dois números de vetores com 20 caracteres de mesmo número e um outro para conter as operações aritméticas. Os resultados das operações com esses vetores devem ser armazenados em um terceiro vetor.
Algoritmo "operacaovetor"

Var
// Seção de Declarações das variáveis 
x : vetor [1..2] de inteiro  //numero x
y : vetor [1..2] de inteiro  //numero y
r: vetor [1..20] de inteiro  //resposta
op: vetor [1..20] de caracter //tipo da operação
i: inteiro     //indice/contador para percorrer vetor

Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
 para i de 1 até 20 faça
 escreval ("Sinal")
 leia(op[i])
 escreval("numero x")
 leia (x[i])
  escreval("numero y")
 leia (y[i])
 se (op[i] = "+") então
 r[i] <- (x[i] + y[i])
 escreval(r[i])
 fimse
 se (op[i] = "-") então
 r[i] <- (x[i] - y[i])
 escreval(r[i])
 fimse
  se (op[i] = "*") então
 r[i] <- (x[i] * y[i])
 escreval(r[i])
 fimse
  se (op[i] = "/") então
 r[i] <- (x[i] div y[i])
 escreval(r[i])
 fimse

 fimpara

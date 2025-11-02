Título: Aplicação de Funções em JavaScript

Aluno: João Vitor Lima Cecilio

Objetivo:
Compreender o uso de funções nomeadas, anônimas e arrow functions em JavaScript, aplicando esses conceitos na resolução de operações matemáticas e manipulação de arrays.

Descrição:
O código desenvolvido realiza operações matemáticas básicas (soma, subtração, multiplicação e divisão) e também manipula dados em um array de números. O objetivo é demonstrar a criação, reutilização e combinação de funções, incluindo o uso de callbacks.

Funções Criadas:
1. Funções Nomeadas
   - soma(a, b), subtracao(a, b), multiplicacao(a, b), divisao(a, b)
     → Realizam operações básicas entre dois números e retornam o resultado.

2. Função Anônima
   - const filtrarPares = function (numeros)
     → Recebe um array e retorna apenas os números pares usando o método .filter().

3. Arrow Function
   - const calcularMedia = (numeros) => { ... }
     → Calcula a média dos valores de um array utilizando .reduce().

4. Função com Callback
   - executarOperacao(a, b, operacao)
     → Recebe dois números e uma função como parâmetro (por exemplo, soma ou multiplicacao), e executa a operação passada como callback.

Conclusão:
O exercício permitiu praticar os diferentes tipos de funções do JavaScript, demonstrando sua flexibilidade, modularidade e potencial para reutilização de código.

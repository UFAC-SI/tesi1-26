# Lista de Exercícios - Aula 03: Fundamentos de Python

**Disciplina:** Tópicos Especiais em Sistemas de Informação - Introdução à Ciência de Dados  
**Professor:** Manoel Limeira de Lima Júnior

---

## Parte 1: Teórica

1. Explique a importância da indentação em Python. O que acontece se ela for feita de forma incorreta?
2. Diferencie uma **Lista** de um **Dicionário**. Em que situações cada um é mais adequado para representar dados?
3. O que significa dizer que Python é uma linguagem de **alto nível** e de **tipagem dinâmica**?
4. Explique o conceito de **fatiamento (slicing)** em listas. Qual o resultado de `lista[1:4]` se a lista for `[10, 20, 30, 40, 50, 60]`?

---

## Parte 2: Prática (Código)

5. Crie um programa que peça ao usuário uma temperatura em Celsius e a converta para Fahrenheit. (Fórmula: `F = C * 1.8 + 32`).
6. Dada a lista `notas = [8.5, 9.0, 6.5, 10.0, 5.0]`, escreva um código que:
    - Adicione a nota `7.5` ao final da lista.
    - Remova a nota `5.0`.
    - Imprima a maior nota da lista.
7. Crie um dicionário chamado `produto` com as chaves `nome`, `preco` e `quantidade`. Calcule o valor total em estoque (preço * quantidade).
8. Escreva uma função chamada `verificar_paridade` que recebe um número inteiro e retorna a string "Par" se o número for par e "Ímpar" se for ímpar.
9. Crie um loop `for` que percorra os números de 1 a 20 e imprima apenas os números que são múltiplos de 3.
10. Importe o módulo `math` e utilize a função `sqrt` para calcular a raiz quadrada de um número fornecido pelo usuário.

---

## Parte 3: Coleções Avançadas

1. **Unicidade com Sets:** Crie uma lista com nomes de cidades, incluindo várias repetições. Escreva um código que utilize um `Set` para exibir apenas os nomes únicos das cidades em ordem alfabética.
2. **Imutabilidade das Tuplas:** Tente alterar um elemento de uma tupla e observe o erro gerado. Explique, com suas palavras, em qual cenário de Ciência de Dados seria importante usar uma tupla em vez de uma lista.
3. **Dicionário de Frequência:** Dada uma string (ex: "ciência de dados é a ciência do futuro"), crie um dicionário que conte quantas vezes cada palavra aparece na frase.


**Dica:** Tente resolver os exercícios práticos no ambiente Jupyter Notebook ou em um script `.py`.

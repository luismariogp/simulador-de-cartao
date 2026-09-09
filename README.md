# Simulador de Cartao de Credito

Projeto desenvolvido em Java para simular compras realizadas em um cartao de credito.

O sistema permite informar o limite do cartao, realizar compras, verificar se existe saldo suficiente e, ao final, exibir as compras realizadas em ordem crescente de valor.

## Tecnologias

- Java
- Git
- GitHub

## Conceitos praticados

- Programacao Orientada a Objetos (POO)
- Classes e objetos
- Encapsulamento
- Construtores
- List e ArrayList
- Comparable
- compareTo
- Collections.sort()
- Estruturas condicionais
- Estruturas de repeticao
- Separacao de responsabilidades

## Funcionamento

O programa solicita ao usuario o limite do cartao e permite cadastrar compras enquanto houver saldo disponivel.

Cada compra possui:

- Descricao
- Valor

As compras sao armazenadas em uma lista e posteriormente ordenadas pelo valor utilizando `Comparable` e `Collections.sort()`.

Ao final, o sistema apresenta as compras realizadas e o saldo atual do cartao.

## Estrutura do projeto

```text
src/
├── CartaoDeCredito.java
├── Compra.java
└── Principal.java
# Swap using Pointers in C

## Description / Descrição
This project implements a function in C that swaps the values of two variables using pointers. Instead of returning values, the function directly modifies the variables through their memory addresses.

Este projeto implementa uma função em C que realiza a troca de valores entre duas variáveis utilizando ponteiros. Em vez de retornar valores, a função modifica diretamente as variáveis através de seus endereços de memória.

## Concepts Applied / Conceitos aplicados
- Pointers (`*` and `&`)
- Pass-by-reference simulation in C
- Direct memory manipulation
---
- Ponteiros (`*` e `&`)
- Simulação de passagem por referência em C
- Manipulação direta de memória


## How It Works / Como funciona
The function receives the memory addresses of two variables and swaps their values using a temporary variable.

A função recebe os endereços de memória de duas variáveis e realiza a troca de seus valores utilizando uma variável auxiliar.

## How to Compile and Run / Como compilar e executar

```bash
gcc src/main.c src/swap.c -Iinclude -o main
./main

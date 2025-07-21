# Lista Encadeada em C

Este projeto implementa uma lista encadeada simples em C, permitindo a inserção de elementos no início, no final e no meio da lista, além de exibir os elementos armazenados.

## Funcionalidades

- **Inserir no início**: Adiciona um novo elemento no início da lista.
- **Inserir no final**: Adiciona um novo elemento no final da lista.
- **Inserir no meio**: Adiciona um novo elemento após um valor de referência.
- **Imprimir lista**: Exibe todos os elementos da lista.

## Estrutura do Código

O código é composto pelas seguintes funções:

- `void inserir_no_inicio(No **lista, int num)`: Insere um elemento no início da lista.
- `void inserir_no_fim(No **lista, int num)`: Insere um elemento no final da lista.
- `void inserir_no_meio(No **lista, int num, int ant)`: Insere um elemento após um valor de referência.
- `void imprimir(No *no)`: Imprime os elementos da lista.

## Como Usar

1. Compile o programa com um compilador C, como `gcc`:
   ```bash
   gcc -o lista_encadeada main.c

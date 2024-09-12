# Sistema Bancário em Python

Este projeto foi desenvolvido como parte de um desafio proposto pela Digital Innovation One (DIO) na trilha de Python. O objetivo do desafio é criar um sistema bancário simples utilizando Python, onde é possível realizar operações básicas como depósito, saque e visualização de extrato.

## Funcionalidades

O sistema bancário possui as seguintes funcionalidades:

1. **Depósito**
   - Permite ao usuário realizar depósitos em sua conta.
   - Apenas valores positivos podem ser depositados.
   - Os depósitos são registrados com a data e o valor, e podem ser visualizados no extrato.

2. **Saque**
   - Permite ao usuário realizar saques, respeitando as seguintes regras:
     - Até 3 saques diários.
     - Limite de R$ 500,00 por saque.
     - Verificação de saldo suficiente antes de realizar o saque.
   - Os saques são registrados com a data e o valor, e podem ser visualizados no extrato.

3. **Extrato**
   - Permite ao usuário visualizar todas as operações realizadas (depósitos e saques).
   - Exibe o saldo atual da conta.

## Regras de Negócio

- **Depósito**: Apenas valores positivos podem ser depositados. O depósito é registrado no extrato com a data e o valor.
- **Saque**: Limite de 3 saques diários e máximo de R$ 500,00 por saque. Verificação de saldo antes de realizar o saque. O saque é registrado no extrato com a data e o valor.
- **Extrato**: Listagem de todos os depósitos e saques realizados. Exibição do saldo atual no final do extrato.

## Como Executar o Projeto

1. Certifique-se de ter o Python instalado em sua máquina.
2. Clone este repositório para o seu ambiente local:

    ```bash
   git clone https://github.com/ronnysenna/sis-bancario.git

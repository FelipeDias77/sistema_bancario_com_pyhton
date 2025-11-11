# 🏦 Sistema Bancário Simplificado com Python

Este projeto é uma solução para o **Desafio de Código 01** do bootcamp **"Luizalabs Back-end com Python"**, uma iniciativa desenvolvida em parceria entre **Luizalabs (Magalu)** e **DIO (Digital Innovation One)**.

Trata-se de um sistema bancário simples, implementado em Python, que simula as operações básicas de uma conta corrente. O foco principal é a organização do código e a aplicação de boas práticas através do uso de **funções** e manipulação de **listas/dicionários** para armazenar dados de usuários e contas.

### ✨ Funcionalidades Implementadas

O sistema permite as seguintes operações através de um menu interativo:

* **Depósito (`d`):** Apenas valores positivos são aceitos.
* **Saque (`s`):**
    * Limitado a **3 saques diários** por conta.
    * Valor máximo de **R$ 500,00** por saque.
    * Verifica se há saldo suficiente.
* **Extrato (`e`):** Exibe todas as movimentações de depósito e saque, formatadas com o valor e o saldo atual.
* **Novo Usuário (`nu`):** Permite cadastrar um novo cliente (CPF, nome, data de nascimento e endereço).
    * Utiliza uma função para **filtrar usuários** e evitar duplicidade de CPF.
* **Nova Conta (`nc`):** Cria uma nova conta corrente (`0001` + número sequencial).
    * Vincula a conta a um **usuário existente** (verificado pelo CPF).
* **Listar Contas (`lc`):** Exibe a agência, número da conta e nome do titular de todas as contas cadastradas.
* **Sair (`q`):** Encerra o programa.

### ⚙️ Destaques de Código e Tecnologias

* **Python 3.x**
* **Funções:** Utilizadas para separar a lógica do programa (`depositar`, `sacar`, `extrato`, etc.).
* **Args e Kwargs:** Uso de *positional-only* (`/`) e *keyword-only* (`*`) para garantir a clareza e obrigatoriedade dos argumentos nas funções.
* **Módulo `textwrap`:** Utilizado para formatar e remover a indentação do menu de forma limpa.# sistema_bancario_com_pyhton

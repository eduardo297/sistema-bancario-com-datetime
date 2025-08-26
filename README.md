# 🏦 Sistema Bancário em Python

Este projeto implementa um **sistema bancário simples** utilizando **Programação Orientada a Objetos (POO)** em Python.  
Ele simula operações de conta corrente com registro de histórico e limites de transações diárias.

---

## 🚀 Funcionalidades

- 👤 **Cadastro de clientes** (Pessoa Física);
- 🏦 **Abertura de contas correntes**;
- 💰 **Depósito** de valores;
- 💸 **Saque** de valores, respeitando limites de saque e saldo;
- 📜 **Extrato detalhado**, incluindo:
  - Tipo da transação,
  - Valor,
  - Data e hora da operação;
- 📅 **Limite de 10 transações diárias** por conta;
- Estrutura orientada a objetos, com **abstração, herança e polimorfismo**.

---

## 📂 Estrutura do Projeto

- `Cliente`, `PessoaFisica` → representam os usuários do banco;  
- `Conta`, `ContaCorrente` → responsáveis pelas operações bancárias;  
- `Historico` → registra e filtra as transações (com data/hora);  
- `Transacao`, `Saque`, `Deposito` → classes que modelam operações financeiras;  
- Funções auxiliares para criar clientes, abrir contas e exibir relatórios.

---

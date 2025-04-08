# 🛒 Projeto: Sistema de Marketplace com Singleton

Este é um projeto simples de um sistema de Marketplace desenvolvido em Python, utilizando o padrão de projeto **Singleton** e seguindo os princípios da **Programação Orientada a Objetos (POO)**.

## 📌 Objetivo

Simular o funcionamento de um marketplace com funcionalidades completas para:
- Cadastrar e remover produtos
- Listar os produtos disponíveis
- Realizar e cancelar pedidos
- Listar todos os pedidos
- Consultar pedidos por comprador

## 🧠 Padrão de Projeto Utilizado

### 🔁 Singleton
O padrão Singleton foi utilizado para garantir que exista apenas **uma instância** da classe `Marketplace`, responsável por gerenciar todos os produtos e pedidos. Isso assegura consistência no controle dos dados da aplicação.

## 🧱 Estrutura de Classes

- `Produto`: Representa um produto com nome e preço.
- `Pedido`: Representa um pedido feito por um comprador.
- `Marketplace`: Classe Singleton que gerencia os produtos e pedidos.
  
## 🖥️ Como Executar

1. Certifique-se de ter o Python instalado (versão 3.6+).
2. Baixe ou clone este repositório:
   ```bash
    https://github.com/juliamzgch/Marketplace-Singleton-.git
   ```
3. Execute o arquivo principal:
   ```bash
     python marketplace.py
   ```
## 🧩 Funcionalidades

- Menu interativo no terminal
- Adição e remoção de produtos
- Listagem de produtos disponíveis
- Realização e cancelamento de pedidos
- Consulta de pedidos por comprador

## 📷 Exemplo de Execução

```
===== MENU DO MARKETPLACE =====
1. Adicionar produto
2. Remover produto
3. Listar produtos
4. Realizar pedido
5. Cancelar pedido
6. Listar pedidos
7. Consultar pedidos por comprador
8. Sair
```

## 📚 Tecnologias Utilizadas

- Python 3.11.4
- Paradigma de Programação Orientada a Objetos
- Padrão de Projeto Singleton

## 👨‍💻 Autores

- Nome: Julia Matias, Ítalo Guilherme, Victor da Mata, Arthur Teixeira e Hugo Gabriel.
- Curso: Paradigmas de Linguagem de Programação
- Ceulp/Ulbra - 25/1

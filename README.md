# 🛒 Projeto: Marketplace com Singleton

Este é um projeto simples de um sistema de Marketplace desenvolvido em Python, utilizando o padrão de projeto **Singleton** e seguindo o paradigma da **Programação Orientada a Objetos (POO)**.

## 📌 Objetivo

Simular o funcionamento básico de um marketplace onde é possível:
- Cadastrar produtos
- Listar os produtos disponíveis
- Realizar pedidos
- Consultar os pedidos feitos

## 🧠 Padrão de Projeto Utilizado

### 🔁 Singleton
Utilizado para garantir que exista apenas **uma instância** do gerenciador central `MarketplaceManager`, que armazena todos os produtos e pedidos. Isso evita inconsistências e facilita o gerenciamento de dados.

## 🧱 Estrutura de Classes

- `MarketplaceManager`: Classe Singleton que gerencia os produtos e pedidos.
- `Produto`: Representa um item que pode ser vendido no marketplace.
- `Cliente`: Representa o comprador.
- `Pedido`: Representa um pedido realizado por um cliente.
  
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
- Cadastro de produtos com nome e preço
- Realização de pedidos com seleção de cliente e produto
- Listagem de produtos e pedidos

## 📷 Exemplo de Execução

```
--- Marketplace ---
1. Adicionar Produto
2. Listar Produtos
3. Realizar Pedido
4. Listar Pedidos
5. Sair
```

## 📚 Tecnologias Utilizadas

- Python 3.11.4
- Paradigma de Programação Orientada a Objetos
- Padrão de Projeto Singleton

## 👨‍💻 Autores

- Nome: Julia Matias, Ítalo Guilherme, Victor da Mata, Arthur Teixeira e Hugo Gabriel.
- Curso: Paradigmas de Linguagem de Programação
- Ceulp/Ulbra - 25/1

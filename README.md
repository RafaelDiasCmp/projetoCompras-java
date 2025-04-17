# 🛒 Projeto Compras em Java

Este projeto é uma aplicação de console desenvolvida em Java que simula um sistema de compras utilizando um cartão de crédito. O usuário pode adicionar produtos, verificar o saldo disponível e visualizar um resumo das compras realizadas.

## 📚 Conceitos Abordados

- **Programação Orientada a Objetos (POO):** Utilização de classes e objetos para modelar entidades como `Produto`, `CartaoDeCredito` e `Compra`.
- **Encapsulamento:** Proteção dos dados das classes através de modificadores de acesso.
- **Listas e Coleções:** Uso da classe `ArrayList` para armazenar e manipular listas de compras.
- **Ordenação de Dados:** Implementação da interface `Comparable` para ordenar as compras por valor.
- **Entrada de Dados:** Leitura de dados do usuário utilizando a classe `Scanner`.

## 🚀 Funcionalidades

- Solicitação do limite do cartão de crédito.
- Adição de produtos com descrição e valor.
- Verificação do saldo disponível antes de cada compra.
- Exibição de mensagem de erro em caso de saldo insuficiente.
- Ordenação das compras por valor.
- Exibição de um resumo das compras realizadas e do saldo restante.

## 🧱 Estrutura do Projeto

- `Produto`: Representa um item que pode ser comprado, contendo descrição e valor.
- `CartaoDeCredito`: Gerencia o limite e o saldo do cartão, além de armazenar as compras realizadas.
- `Compra`: Representa uma transação de compra, implementando a interface `Comparable` para permitir a ordenação por valor.
- `Main`: Classe principal que contém a lógica de interação com o usuário.

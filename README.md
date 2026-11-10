# 📦 Gerenciador de Inventário de Produtos

Este é um projeto simples e eficiente em Python para gerenciar listas de produtos e preços de uma loja. O sistema permite cadastrar novos itens via entrada do usuário e remover o último item cadastrado, mantendo o controle do estoque de forma dinâmica.

## 🚀 Funcionalidades

- **Visualização de Estoque:** Listagem atualizada de todos os produtos e seus respectivos preços.
- **Cadastro Dinâmico:** Adição de novos produtos e preços através de inputs interativos.
- **Remoção Simplificada:** Remoção rápida do último item adicionado utilizando o conceito de pilha (`pop`).

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Estruturas de Dados:** Listas (`list`)
- **Iteradores:** `zip()` para pareamento de chaves e valores

## 📋 Como Funciona?

O projeto está estruturado em três etapas principais:

1. **Inicialização:** Criação das listas base com produtos e valores padrão.
2. **Entrada de Dados:** Menu interativo para receber o nome e o preço do novo produto, adicionando-os ao final das listas.
3. **Exclusão:** Função para deletar o último item cadastrado no sistema, útil para desfazer erros rápidos.

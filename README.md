Projeto: Sistema de Gerenciamento de Biblioteca

Descrição

Este projeto é um sistema completo para gerenciar bibliotecas, com funcionalidades de CRUD para livros e usuários, registro de empréstimos, geração de relatórios de livros mais emprestados e persistência de dados usando arquivos JSON.

Tecnologias Utilizadas

Linguagem: Python

Estrutura de Dados: Dicionários e listas

Persistência: Arquivos JSON

Funcionalidades Principais

CRUD de Livros:

Adicionar, editar, deletar e listar livros.

Cada livro contém os atributos: código, título, autor e quantidade disponível.

CRUD de Usuários:

Adicionar, editar, deletar e listar usuários.

Cada usuário é identificado por um código e um nome.

Registro de Empréstimos:

Registrar empréstimos de livros para usuários.

Controle de prazo de devolução com 14 dias a partir da data de empréstimo.

Relatórios:

Exibir os livros mais emprestados com base no histórico de empréstimos.

Persistência de Dados:

Salvar e carregar dados de livros, usuários e empréstimos em um arquivo JSON.

Como Executar

Instale o Python (versão 3.7 ou superior).

Clone ou baixe o repositório.

Execute o arquivo principal:

python biblioteca.py

Interaja com o sistema através do terminal.

Possíveis Melhorias

Adicionar interface gráfica.

Implementar notificações de prazo de devolução.

Integração com banco de dados relacional.

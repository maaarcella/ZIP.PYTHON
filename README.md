# Sistema de Cadastro de Usuários em Python

## Descrição

Este projeto consiste em um sistema simples de cadastro de usuários desenvolvido em Python para execução no terminal. O programa permite registrar informações de usuários, armazenando nome, e-mail e senha em listas durante a execução do sistema.

O usuário interage com o programa por meio de um menu de opções, podendo cadastrar novos usuários, visualizar os registros existentes ou encerrar a aplicação.

## Funcionalidades

* Cadastro de usuários;
* Armazenamento de nome, e-mail e senha;
* Listagem de todos os usuários cadastrados;
* Interface simples baseada em terminal;
* Encerramento do programa por opção do usuário.

## Tecnologias Utilizadas

* Python 3
* Biblioteca padrão `os`

## Objetivo do Projeto

O objetivo deste projeto é praticar conceitos básicos da linguagem Python, especialmente a manipulação de listas, estruturas condicionais, laços de repetição e entrada de dados pelo usuário.

Durante o desenvolvimento foram aplicados conhecimentos relacionados à criação de menus interativos, armazenamento de informações em memória e exibição organizada de dados.

## Como Funciona

Ao iniciar o programa, o usuário encontra um menu com três opções:

1. Cadastrar usuário;
2. Listar usuários cadastrados;
3. Finalizar o programa.

As informações inseridas são armazenadas em listas separadas para nome, e-mail e senha. Quando a opção de listagem é selecionada, o sistema exibe todos os usuários cadastrados utilizando a função `zip()` para percorrer os dados simultaneamente.

## Aprendizados

Este projeto permitiu praticar:

* Estruturas de repetição (`while`);
* Estruturas condicionais (`if`, `elif`);
* Manipulação de listas;
* Entrada e saída de dados;
* Utilização da função `zip()`;
* Organização lógica de programas simples.

## Melhorias Futuras

* Validação de e-mails;
* Ocultação de senhas durante o cadastro;
* Exclusão e edição de usuários;
* Login com autenticação;
* Armazenamento em arquivos ou banco de dados;
* Interface gráfica.

Este projeto possui finalidade educacional e serve como base para sistemas mais completos de gerenciamento e autenticação de usuários.

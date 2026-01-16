# Sistema Web de Agenda de Contatos

Projeto Java Web desenvolvido para gerenciar contatos, permitindo cadastrar, listar, editar e excluir informações, além de gerar relatórios em PDF. A aplicação foi construída seguindo o padrão MVC e utiliza banco de dados relacional para persistência dos dados.

## O que o sistema faz
- Cadastra novos contatos
- Lista os contatos cadastrados
- Permite editar informações de um contato
- Exclui contatos do sistema
- Gera um relatório em PDF com a lista de contatos

## Tecnologias utilizadas
- Java
- Servlets e JSP
- JDBC
- MySQL
- Apache Tomcat
- iText
- Git

## Estrutura do projeto
O projeto segue o padrão MVC (Model-View-Controller):
- Model: JavaBeans e classes DAO responsáveis pelo acesso aos dados
- View: JSP para exibição das telas
- Controller: Servlets responsáveis pelo controle de fluxo da aplicação

## Banco de dados
- MySQL
- Operações CRUD implementadas com JDBC
- Uso do padrão DAO

## Execução e deploy
- Aplicação empacotada em formato WAR
- Executada em Apache Tomcat
- Deploy realizado em ambiente Linux

## Como executar
1. Clone o repositório
2. Importe o projeto na IDE
3. Configure o banco de dados MySQL
4. Ajuste as credenciais de conexão
5. Execute o projeto no Apache Tomcat

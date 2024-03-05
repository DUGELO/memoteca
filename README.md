# Memoteca

Este é um projeto de uma memoteca desenvolvido em Angular. A memoteca é uma aplicação web que permite aos usuários cadastrar, visualizar, editar e excluir memórias.

## Funcionalidades

- Cadastro de memórias
- Visualização de memórias
- Edição de memórias
- Exclusão de memórias

## Tecnologias utilizadas

- Angular
- Angular CLI
- HTML
- CSS
- TypeScript
- JSON Server

## Como executar o projeto

1. Clone este repositório
2. Instale as dependências com o comando `npm install`
3. dentro da pasta "backend" execute o comando `json-server --watch db.json` para iniciar o servidor JSON
5. Em outro terminal,na pasta "memoteca" execute o comando `ng serve` para iniciar o servidor de desenvolvimento do Angular
6. Acesse a aplicação em `http://localhost:4200`

Certifique-se de ter o JSON Server instalado globalmente em sua máquina. Caso não tenha, você pode instalá-lo com o comando `npm install -g json-server`.

## Configuração do JSON Server

O JSON Server será responsável por criar uma API RESTful a partir do arquivo `db.json`. Certifique-se de que o arquivo `db.json` esteja corretamente configurado com os dados da sua memoteca.

## Consumindo a API com o Angular

No projeto Angular, utilize o `HttpClient` para fazer as requisições HTTP para a API criada pelo JSON Server. Você pode encontrar exemplos de como fazer isso nos componentes relacionados às funcionalidades de cadastro, visualização, edição e exclusão de memórias.

## Contribuição

Contribuições são sempre bem-vindas! Se você encontrou algum bug, tem alguma sugestão de melhoria ou deseja adicionar uma nova funcionalidade, fique à vontade para abrir uma issue ou enviar um pull request.

## Créditos

Este projeto foi desenvolvido com base no curso "Angular 14: aplique os conceitos e desenvolva seu primeiro CRUD" da [Alura](https://www.alura.com.br/). Agradeço à [Nayanne Batista](https://github.com/NayanneBatista), instrutora do curso, por compartilhar seus conhecimentos e contribuir para o meu aprendizado.

Link para o curso: [Angular 14: aplique os conceitos e desenvolva seu primeiro CRUD](https://cursos.alura.com.br/course/angular-explorando-framework)

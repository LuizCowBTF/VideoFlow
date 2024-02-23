# VídeoFlow

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white) ![JSON](https://img.shields.io/badge/JSON-black?style=for-the-badge&logo=JSON%20web%20tokens)

## Aplicativo de Streaming de Vídeos e Filmes baseado em HTML5, CSS3 e JavaScript

### O VídeoFlow é um Streaming de Vídeos e Filmes com busca e filtros. É um MVP que tá só começando e ainda tem muitas funcionalidades novas para serem desenvolvidas. Utilzo o JSON-SERVER para BackEnd no formato .json.

### Baseado em curso de formação para atualização profissional chamado “JavaScript: consumindo e tratando dados de uma API”, disponibilizado pela Alura e ministrado pela instrutora Rafaela Petelin Silvério. Nesta oportunidade pude atualizar meus conhecimentos em:

* Aprenda a consumir uma API com JavaScript
* Crie filtros dinâmicos para os dados da API
* Faça a tradução de um layout predefinido em uma aplicação funcional
* Utilize async await para criar funções assíncronas
* Construa uma plataforma de compartilhamento de vídeos
* Conheça as Promises e seus métodos
* Trate possíveis erros de requisição retornados da API
* Essa é ma API Rest mockada, utilizando JSON-SERVER.

## 🛠️ Instalação

```bash
$ cd backend
$ npm install -g json-server
$ json-server --watch videos.json
```

## 🛠️ Como utlizar

### No arquivo INDEX.HTML dentro do sub-menu a opção abaixo:

```
Open with Live Server
```

Você pode fazer isso efetuando uma requisição post utilizando o POSTMAN para:

```
POST http://localhost:3000/videos
```


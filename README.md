# AuthNodeJWT

## Projeto Desenvolvido no Curso do [Matheus Battisti](https://www.youtube.com/watch?v=qEBoZ8lJR3k)

## Sobre o Projeto
durante uma aula do canal [Hora de codar](https://www.youtube.com/@MatheusBattisti) no YouTube. A API desenvolvida é um exemplo de como criar 
uma API com token utilizando a linguagem JavaScript e o framework Node.js com o Mongoose para interagir com o MongoDB. 
Este projeto é um exemplo de autenticação de usuários em uma aplicação web, utilizando Node.js e JWT (JSON Web Tokens). 
A autenticação é uma funcionalidade importante em muitas aplicações, pois garante que apenas usuários autorizados tenham
acesso a determinadas funcionalidades.

## Funcionalidades

- Registro de Usuário: permite que um novo usuário crie uma conta na aplicação, fornecendo um nome de usuário e uma senha.
- Login de Usuário: permite que um usuário autenticado faça login na aplicação, fornecendo o nome de usuário e a senha cadastrados.
- Proteção de Rotas: uma vez autenticado, o usuário pode acessar rotas protegidas na aplicação, como páginas de perfil ou funcionalidades específicas.
- Token JWT: a autenticação utiliza um token JWT (um tipo de código) que contém informações sobre o usuário e o seu estado de autenticação. Esse token é enviado
para o cliente (o navegador, por exemplo) e é utilizado em todas as requisições subsequentes para verificar a autenticidade do usuário.

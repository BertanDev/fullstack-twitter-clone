# 🐦 Twitter Fullstack Clone 🐦

Aplicação criada durante curso do canal gringo [Code With Antonio](https://www.youtube.com/@codewithantonio), onde criamos um clone do Twitter, tanto front-end quanto back-end utilizando o Framework NextJS     

<br/>

## ▶️ Testar aplicação 

> **Note**                
> Para rodar a aplicação em sua máquina local, é necessário criar uma database no serviço [MongoDB Atlas](https://cloud.mongodb.com/)

Crie seu arquivo .env com as seguinte informações:
```
DATABASE_URL="MONGO URL CONNECTION"
NEXTAUTH_JWT_SECRET="NEXT_AUTH_JWT_SECRET"
NEXTAUTH_SECRET="NEXT_AUTH_SECRET"
```

Com o projeto no seu computador, rode na raíz:
```
npm install
```

em seguinda:
```
npm run dev
```

## 💠 Rotas API

  - [x] GET ```/api/posts``` retorna os posts de um usuário
  - [x] GET ```/api/notifications/:userId``` retorna as notificações do usuário
  - [x] GET ```/api/users``` retorna os usuários cadastrados na aplicação
  - [x] GET ```/api/users/:userId``` retorna os dados de um usuário
  - [x] GET ```/api/current``` retorna os dados do usuário logado

  - [x] POST ```/api/register``` cria um novo usuário
  - [x] POST ```/api/like``` adiciona um novo like na publicação e cria um notificação
  - [x] POST ```/api/follow``` adiciona um novo seguidor a um usuário e cria um notificação
  - [x] POST ```/api/comments``` adiciona um novo comentário a uma publicação e cria um notificação
  - [x] POST ```/api/posts``` cria um novo post

  - [x] DELETE ```/api/like``` remove um like da publicação
  - [x] DELETE ```/api/follow``` remove um seguidor de um usuário
  
  - [x] PATCH ```/api/edit``` edita o perfil do usuário
  
  
  
 
  


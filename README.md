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

  - [x] Todo fluxo de autenticação é feito utilizando next-auth
  
## 🔱 Ferramentas utilizadas

  - NextJS
  - Typescript
  - Next-auth
  - Prisma
  - Axios
  - Bcrypt
  - Date-fns
  - React-dropzone
  - React-hot-toast
  - React Icons
  - React Spinners
  - Swr
  - Tailwindcss
  - Zustand
  - MongoDB

## Telas da aplicação
  
### Tela inicial, usuário não logado
![inicial](https://user-images.githubusercontent.com/72395637/232176666-aba3494f-c474-4769-b6c0-e5081d8236d6.jpg)

## Modal de login
![loginModal](https://user-images.githubusercontent.com/72395637/232176714-550e7f3f-9adb-4f8c-9123-a756555066bf.png)

## Modal de registro
![register](https://user-images.githubusercontent.com/72395637/232176780-5ffe8e73-a492-4768-99ef-aef6b3e4c66c.jpg)

## Tela inicial, usuário Logado
![homeLogged](https://user-images.githubusercontent.com/72395637/232177206-fa0bcb41-35f4-4e2b-83f6-cbdbfead6766.jpg)

## Tela seu perfil
![myProfile](https://user-images.githubusercontent.com/72395637/232177248-2c219e7c-4b14-4747-a00e-601bf2de34a8.jpg)

## Tela perfil outro usuário
![otherProfile](https://user-images.githubusercontent.com/72395637/232177256-7e8e6280-b798-4a6e-a2e1-bd0253d9f70e.jpg)

## Modal para editar perfil
![modalEdit](https://user-images.githubusercontent.com/72395637/232177280-3b8bf938-de03-4c2f-80d7-ad6a2280e62c.jpg)

## Tela para comentar em um post
![comment](https://user-images.githubusercontent.com/72395637/232177314-ecf6f440-bfae-4eff-a5c4-fce6fce55692.jpg)

### Tela de notificações
![notifications](https://user-images.githubusercontent.com/72395637/232177326-9097927c-5c70-4232-a4d0-fd73cf4f1aa0.jpg)

  


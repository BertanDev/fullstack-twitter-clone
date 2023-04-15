# 🐦 Twitter Fullstack Clone 🐦

Aplicação criada durante curso do canal gringo [Code With Antonio](https://www.youtube.com/@codewithantonio), onde criamos um clone do Twitter, tanto front-end quanto back-end utilizando o Framework NextJS

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

  - [x] POST ```/api/register``` cria um novo usuário


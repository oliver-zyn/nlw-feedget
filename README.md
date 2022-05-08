# FeedGet

![image](https://user-images.githubusercontent.com/89222905/167318566-26e4c1cc-8253-4880-939a-ae288f243c56.png)

## 📖 Sobre

Um projeto criado juntamente com a <a href="https://www.rocketseat.com.br">rocketseat</a> durante a nlw return. O evento durou 1 semana e trouxe diversos novos aprendizados para mim, fazendo a trilha impulse.

A aplicação consiste em um widget que envia feedbacks para os donos da página, podendo ser reutilizado em diversas outras aplicações. Contém tanto o front-end (react.js) e back-end (node.js) com banco de dados (postgresql).

Site em produção: https://feedget-nlw.netlify.app

## 💻 Tecnologias utilizadas

- React.js
- Tailwind Css
- TypeScript
- Vite
- Axios
- Phosphor Icons
- Prisma
- PostgreSQL
- Nodemailer
- Jest
- SOLID

## ⚒️ Features

- Widget para escolha do tipo de feedback
- Tipos de feedback: problema, ideia e outro
- Descrição do feedback em formulário
- Funcionalidade para tirar uma screenshot da tela atual do usuário
- Envio das informações através da rota /feedbacks
- Armazenamento do feedback em banco de dados relacional
- Envio de email contendo as informações do feedback

## 🖋️ Layout

Você pode vizualizar o layout do projeto realizado no figma através <a href="https://www.figma.com/community/file/1102912516166573468">desse link</a>

## ⚙️ Executando o projeto

Primeiramente, deve-se instalar todas as dependências (tanto do frontend, quando no back-end):
```
npm install
```

### Front-end (web):

Configurar arquivo .env.local com a variável ambiente VITE_API_URL, sendo essa a url da API do nosso backend.

Rodando o projeto:
```
npm run dev
```
Realizando build:
```
npm run build
```

### Back-end (server):

Configurar arquivo .env com a variável DATABASE_URL, sendo essa a url de conexão do nosso banco de dados postgreSQL.

Rodando o projeto:
```
npm run dev
```
Realizando build:
```
npm run build
```
Executanto testes automatizados:
```
npm run test
```

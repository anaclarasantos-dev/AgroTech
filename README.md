# AgroTech 🌱

Sistema Web desenvolvido para a empresa **AgroTech**, com backend em Node.js, banco de dados MySQL e aplicação mobile integrada.

 Projeto originalmente desenvolvido há alguns anos e recentemente **revisitado** para atualização do ambiente, dependências e configuração do banco de dados, garantindo que o sistema execute corretamente com a stack atual.

---

## 🛠️ Tecnologias Utilizadas

- Node.js 
- MySQL (XAMPP)
- Prisma ORM
- Expo (Mobile)
- VS Code
- Insomnia (testes de API)
- Git & GitHub

---

## 📋 Pré-requisitos

Antes de executar o projeto, é necessário ter instalado:

- Node.js, XAMPP, VS Code e Insomnia (para testes de API)

---

## ⚙️ Configuração do Ambiente !IMPORTANTE

Abra o **XAMPP Control Panel** e inicie:
- Apache  
- MySQL  

---
## 🌐 Executando o Banco de dados (SQL)

1. Abra o **XAMPP Control Panel**
1. No XAMPP, clique em **Admin** no MySQL para abrir o **phpMyAdmin**
2. Crie um banco de dados com o nome: Agrotech

No backend, o Prisma é responsável por criar as tabelas automaticamente.

Dentro da pasta `AgroTech/back`, execute:

`npx prisma db push`

## 🌐 Executando o Backend (API)

Dentro da pasta do projeto, execute:
`
cd AgroTech/back
npm install
npx nodemon`

## 🌐 Executando o Frontend (Web)

1. Abra o arquivo `index.html` dentro da pasta *Login*
2. Clique com o botão direito
3. Selecione **Open with Live Server**

## 📱 Executando o Mobile

Dentro da pasta `mobileAgro`:

1. Instale as bibliotecas necessárias:
   - Async Storage
   - CryptoJS
   - NavigationContainer
   - createNativeStackNavigator
   - createMaterialTopTabNavigator

2. Execute o comando:
   
`expo start --web`

*📌Projeto desenvolvido para fins acadêmicos e de aprendizado prático em desenvolvimento web e mobile.*



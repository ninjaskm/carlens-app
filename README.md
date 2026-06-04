<div align="center">

<img src="logo.png" width="120" alt="CarLens Logo"/>

# CarLens

**Compare carros com facilidade**

![Android](https://img.shields.io/badge/Android-Kotlin-7B2FBE?style=for-the-badge&logo=kotlin&logoColor=white)
![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-7B2FBE?style=for-the-badge)

</div>

---

## 📱 Sobre o Projeto

O **CarLens** é um aplicativo mobile Android para pesquisa, cadastro e **comparação técnica de veículos**. A proposta é centralizar informações de carros em um único lugar, permitindo que o usuário compare especificações lado a lado antes de tomar uma decisão de compra.

O app surgiu como projeto acadêmico e está sendo evoluído para um produto real, com sistema de anúncios integrado via AdMob e melhorias contínuas de UI/UX.

---

## ✨ Funcionalidades

- 🔐 **Autenticação** — login e cadastro de usuários com JWT + Bcrypt
- 🚗 **Listagem de carros** — catálogo com imagens, preço (Tabela FIPE), tipo e combustível
- 🔍 **Pesquisa com filtros** — busca por marca, modelo e características
- ⭐ **Recomendações personalizadas** — sugestões baseadas no perfil do usuário
- ⚖️ **Comparação técnica** — compare dois veículos lado a lado com destaque visual para vantagens e desvantagens
- ➕ **Cadastro de veículos** — formulário completo enviado para aprovação administrativa
- 🔗 **Redirecionamento** — links diretos para OLX e WebMotors
- 📢 **Anúncios integrados** — monetização via Google AdMob

---

## 🖼️ Screenshots

| Login | Cadastro | Home |
|-------|----------|------|
| <img src="screenshots/login.jpg" width="200"/> | <img src="screenshots/cadastro.jpg" width="200"/> | <img src="screenshots/home.jpg" width="200"/> |

| Pesquisa | Seleção | Comparação |
|----------|---------|------------|
| <img src="screenshots/pesquisa.jpg" width="200"/> | <img src="screenshots/comparacao1.jpg" width="200"/> | <img src="screenshots/comparacao2.jpg" width="200"/> |

---

## 🛠️ Stack Tecnológica

### Mobile (Android)
- **Kotlin** — linguagem principal
- **Retrofit** — consumo da API REST
- **Glide** — carregamento e cache de imagens
- **AdMob** — sistema de anúncios
- **Arquitetura MVVM**

### Backend (API REST)
- **Node.js + Express** — servidor e rotas
- **MongoDB Atlas + Mongoose** — banco de dados NoSQL
- **JWT** — autenticação stateless
- **Bcrypt** — hash de senhas
- **Hospedado no Render**

---

## 🚀 Roadmap

- [x] Autenticação JWT
- [x] Listagem e pesquisa de veículos
- [x] Sistema de comparação técnica
- [x] Recomendações personalizadas
- [x] Cadastro de veículos com aprovação admin
- [x] Integração AdMob
- [x] Redirecionamento OLX / WebMotors
- [ ] Publicação na Google Play Store
- [ ] Melhorias de UI/UX
- [ ] Expandir base de veículos

---

## 👨‍💻 Desenvolvido por

**Matheus Cavalcanti Campos** — Backend (API REST, autenticação JWT, integração MongoDB)

[![GitHub](https://img.shields.io/badge/GitHub-ninjaskm-181717?style=flat&logo=github)](https://github.com/ninjaskm)

---

<div align="center">
  <sub>Projeto acadêmico em evolução • UNINASSAU Recife • 2025</sub>
</div>

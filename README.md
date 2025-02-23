# MechTune - Sistema de Gerenciamento de Oficina

Este é um sistema para gerenciar ordens de serviço de uma oficina mecânica. Ele permite registrar veículos, proprietários, ordens de serviço e acompanhar revisões de forma organizada.

## 🚀 Tecnologias Utilizadas

- **Next.js** - Frontend Web
- **React Native** - Aplicativo Mobile
- **Node.js + Express** - Backend
- **PostgreSQL** - Banco de Dados SQL
- **Sequelize** - ORM para manipulação do banco

## 📂 Estrutura do Projeto

- **backend/** → API REST com Node.js e Express
- **frontend/** → Interface Web com Next.js
- **mobile/** → Aplicativo para mecânicos em React Native

## 📌 Funcionalidades Principais

✅ Gerenciamento de ordens de serviço (OS)  
✅ Cadastro de veículos e proprietários  
✅ Checklist de revisão ao abrir uma OS  
✅ Edição concorrente para evitar conflitos  
✅ Histórico de peças utilizadas nos veículos  
✅ Controle de valores de serviços e peças  

## 🛠 Como Rodar o Projeto

### 1️⃣ Clonar o Repositório
```bash
 git clone https://github.com/seu-usuario/mechtune.git
 cd mechtune
```

### 2️⃣ Configurar o Backend
```bash
 cd backend
 npm install
 npm run dev
```

### 3️⃣ Configurar o Frontend
```bash
 cd frontend
 npm install
 npm run dev
```

### 4️⃣ Configurar o Mobile
```bash
 cd mobile
 npm install
 npx expo start
```

## 📌 Próximos Passos
- [ ] Implementar CRUD de Ordens de Serviço
- [ ] Criar autenticação de usuários
- [ ] Desenvolver interface do checklist no app mobile

---
**Autor:** Mateus Umbria


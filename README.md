# NestJS User API

API criada com Node.js e NestJS para cadastro e gerenciamento de usuários em memória.

## 👨‍🎓 Alunos

- Nome: Gabriel Ntan Candido de Souza  
  E-mail: gabriel.natan@aluno.faculdadeimpacta.com.br

---

## 🚀 Como rodar o projeto

```
npm install
npm run start:dev
```

A aplicação estará disponível em:  
http://localhost:3000

---

## 🔁 Rotas da API

### Criar usuário

- **POST** `/users`
- **Body:**

```
{
  "name": "Ana Souza",
  "email": "ana@example.com"
}
```

---

### Editar usuário

- **PUT** `/users/:id`
- **Body:**

```
{
  "name": "Ana Souza Atualizada",
  "email": "ana.nova@example.com"
}
```

---

### Listar todos os usuários

- **GET** `/users`

---

### Obter um usuário

- **GET** `/users/:id`

---

### Deletar um usuário

- **DELETE** `/users/:id`

---

## 📦 Armazenamento

Este projeto armazena os usuários apenas **em memória**, sem banco de dados.

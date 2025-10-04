# 📧 Mail Service

Serviço responsável pelo **envio de e-mails** transacionais, como:
- Boas-vindas ao novo usuário.
- Confirmação de aluguel de livro.

Ele escuta mensagens do **RabbitMQ** enviadas pelo **Library Service** e envia os e-mails correspondentes.

---

## 🚀 Tecnologias Utilizadas
- NestJS
- TypeScript
- Nodemailer
- Pug (templates)
- RabbitMQ
- Docker
- Brevo / SendinBlue (SMTP gratuito opcional)

---

## ⚙️ Como Rodar o Projeto
npm run dev


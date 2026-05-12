# 🩺 Agendamento de Consultas

Sistema simples para gerenciamento de consultas em clínicas e consultórios com poucos profissionais.

A aplicação permite que pacientes realizem agendamentos e que profissionais organizem sua agenda de atendimento de forma prática e eficiente.

---

## 📌 Funcionalidades

- Cadastro de profissionais
- Cadastro de pacientes
- Cadastro de especialidades
- Definição de horários de atendimento
- Agendamento de consultas
- Validação de conflitos de horários
- Listagem de consultas do dia

---

## 👥 Perfis do Sistema

### Profissional
- Gerenciar agenda
- Definir horários disponíveis
- Visualizar consultas agendadas

### Paciente
- Visualizar horários disponíveis
- Agendar consultas

---

## 🧠 Regra de Negócio

Cada consulta vincula:

- Paciente
- Profissional
- Horário

O sistema valida automaticamente se o profissional já possui atendimento marcado no horário selecionado.

---

## 🎯 Objetivo do Projeto

Projeto desenvolvido para fins acadêmicos e prática de conceitos como:

- CRUD
- Modelagem de sistemas
- Relacionamento entre entidades
- Regras de negócio
- Desenvolvimento Full Stack

---

## 🛠️ Tecnologias

> As tecnologias podem variar conforme a implementação do projeto.

Exemplo:

- Java / Spring Boot
- Node.js
- React
- MySQL
- HTML / CSS / JavaScript

---

## 📂 Estrutura Base

```bash
src/
 ├── controllers/
 ├── services/
 ├── repositories/
 ├── models/
 └── views/
```

---

## 🚀 Status do Projeto

🚧 Em desenvolvimento

---

## 📄 Licença

Projeto acadêmico para estudos e aprendizado.

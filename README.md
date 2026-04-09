# 🦴 FlexPedia

FlexPedia é um catálogo colaborativo e gratuito de exercícios de fisioterapia, criado com o objetivo de ser uma ferramenta de utilidade pública para profissionais e estudantes da área.

A ideia central é simples: qualquer pessoa pode sugerir exercícios, mas apenas fisioterapeutas com registro ativo no CREFITO podem validar e aprovar o conteúdo — garantindo qualidade e segurança nas informações disponibilizadas.

---

## 💡 Motivação

A fisioterapia carece de uma base colaborativa, acessível e confiável de exercícios terapêuticos. O FlexPedia nasce pra preencher esse espaço, sendo desenvolvido de forma aberta e sem fins lucrativos.

---

## ⚙️ Stack

**Backend (Fase 1)**
- Java 17
- Spring Boot 3
- Spring Security + JWT
- Spring Data JPA
- PostgreSQL
- Docker

**Mobile (Fase 2)**
- Kotlin
- Android

---

## 👥 Perfis de usuário

| Role | Permissões |
|------|-----------|
| USER | Cadastrar e visualizar exercícios |
| CREFITO | Aprovar ou rejeitar exercícios, convidar outros profissionais |
| ADMIN | Gerenciar usuários e promover contas CREFITO |

---

## 📋 Roadmap

- [x] Criação do repositório e setup inicial
- [ ] Modelagem do banco de dados
- [ ] Autenticação com Spring Security + JWT
- [ ] Sistema de roles e permissões
- [ ] CRUD de exercícios
- [ ] Fluxo de aprovação de exercícios
- [ ] Testes unitários
- [ ] Documentação com Swagger
- [ ] Dockerização da aplicação
- [ ] App Android em Kotlin

---

## 🤝 Objetivo futuro

Estabelecer parceria com o COFFITO (Conselho Federal de Fisioterapia e Terapia Ocupacional) para integração de uma API oficial de validação de registro profissional, tornando o processo de verificação de credenciais automatizado e ainda mais confiável.

---

## 📄 Licença

MIT — livre para usar, estudar e contribuir.

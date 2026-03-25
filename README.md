<div align="center">

# 🌆 SampaTech

### Conectando desenvolvedores através de eventos tech em São Paulo

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Contributors](https://img.shields.io/github/contributors/sampatech-hub/.github)](https://github.com/sampatech-hub/.github/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/sampatech-hub/.github)](https://github.com/sampatech-hub/.github/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/sampatech-hub/.github/pulls)
[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)](https://github.com/sampatech-hub/.github)

🇧🇷 Português | 🇺🇸 English (coming soon)

</div>

---

## 📩 Enviar Evento

Conhece um evento de tecnologia em São Paulo? **Compartilhe com a comunidade em menos de 2 minutos!**

> 👉 [Abra uma Issue aqui](https://github.com/sampatech-hub/.github/issues/new) e cole o link do evento. Simples assim. ⏱️

**O que incluir:**
- 📌 Nome do evento
- 🗓️ Data e horário
- 🔗 Link de inscrição ou informações
- 📍 Local (ou "Online")

Toda submissão é revisada e adicionada à plataforma. **Leva menos de 2 minutos.**

---

## 🤔 O que é o SampaTech?

**SampaTech** é uma plataforma open-source criada para **centralizar e divulgar eventos de tecnologia em São Paulo, Brasil**.

Seja um hackathon, meetup, palestra ou workshop — o SampaTech é o lugar para descobrir, compartilhar e nunca perder um evento tech na cidade.

Acreditamos que **grandes comunidades são construídas por experiências compartilhadas**. O SampaTech é a nossa contribuição para tornar a cena tech paulistana mais conectada, acessível e visível para todos.

---

## ⚙️ Como Funciona

### Hoje

- Eventos são enviados pela comunidade via **GitHub Issues**
- Cada submissão é **revisada manualmente** pelos mantenedores
- Após aprovação, o evento é divulgado para toda a comunidade

### Em breve

- **API REST** para listagem e busca de eventos
- **Plataforma web** para navegação e filtragem
- **Recomendações inteligentes** baseadas em interesses do usuário

> O projeto começa simples e evolui junto com a comunidade. Sem hype, só entrega.

---

## 🔗 API / Status do Projeto

> ⚠️ **Em desenvolvimento ativo** — o projeto está crescendo e evoluindo.

| Recurso | Status |
|---|---|
| Submissão de eventos via Issues | ✅ Disponível |
| `GET /events` | 🚧 Em desenvolvimento |
| Documentação Swagger | 📋 Planejado |
| Autenticação de usuários | 📋 Planejado |
| Frontend web | 📋 Planejado |

---

## 🧱 Arquitetura

O SampaTech começa como um **monolito bem estruturado** — simples, funcional e fácil de entender para novos contribuidores.

```
sampatech/
├── src/
│   ├── controller/    # Endpoints REST
│   ├── service/       # Regras de negócio
│   ├── repository/    # Acesso ao banco de dados
│   └── model/         # Entidades do domínio
├── resources/
│   └── application.yml
└── ...
```

**Stack atual:**
- **Spring Boot** — backend e API REST
- **PostgreSQL** — banco de dados relacional
- Arquitetura monolítica, podendo evoluir conforme a demanda

> Nada de microserviços prematuros. Fazemos o básico bem feito primeiro.

---

## ⚙️ Stack Tecnológica

| Camada | Tecnologia |
|---|---|
| Backend | Java + Spring Boot |
| Banco de Dados | PostgreSQL |
| Cloud *(futuro)* | AWS |
| Frontend *(planejado)* | A definir |

---

## 🤝 Como Contribuir

> **O open source é uma das melhores formas de crescer como dev — e o SampaTech é a sua oportunidade.**

Contribuir aqui significa experiência real com:
- ✅ Fluxo Git (branch, commit, rebase)
- ✅ Pull Requests e code review
- ✅ Trabalho colaborativo em equipe
- ✅ Produto real utilizado por uma comunidade
- ✅ Portfólio público que se destaca

**Iniciante? Perfeito. Temos issues marcadas como `good first issue` esperando por você.**

### Passo a passo

```bash
# 1. Faça um Fork
# Clique em "Fork" no canto superior direito desta página

# 2. Clone o seu fork (atenção: o repositório se chama ".github")
git clone https://github.com/SEU_USUARIO/.github.git
cd .github

# 3. Crie uma branch para sua contribuição
git checkout -b feat/nome-da-sua-feature

# 4. Faça suas alterações e commite
git add .
git commit -m "feat: descreva sua mudança"

# 5. Envie para o seu fork
git push origin feat/nome-da-sua-feature

# 6. Abra um Pull Request
# Acesse o repositório original e abra um PR a partir da sua branch
```

Não sabe por onde começar? Veja as [issues abertas](https://github.com/sampatech-hub/.github/issues) — algumas têm a label `good first issue` só para você. 🙌

---

## 🏆 Hall da Fama

> Estas são as pessoas que ajudaram a construir o SampaTech. Você pode ser o próximo.

| Contribuidor | Badge |
|---|---|
| [@sampatech-hub](https://github.com/sampatech-hub) | 🥇 Founder Contributor |
| *(seu nome aqui)* | 🥈 Early Adopter |
| *(seu nome aqui)* | 🥉 Community Builder |

*O Hall da Fama é atualizado a cada contribuição significativa. Abra um PR e garanta o seu lugar.*

---

## 🎖️ Sistema de Badges

Contribuidores do SampaTech ganham badges exclusivos como reconhecimento pelo seu trabalho. **Quanto mais você contribui, mais você conquista.**

| Badge | Como Ganhar |
|---|---|
| 🏅 **First PR** | Ter o primeiro pull request aceito |
| 🌟 **Event Curator** | Submeter 3+ eventos válidos |
| 🔧 **Bug Slayer** | Corrigir um bug reportado |
| 🚀 **Feature Builder** | Implementar uma nova funcionalidade |
| 🧠 **Core Contributor** | Ter 5+ PRs aceitos |
| 👑 **Founder Contributor** | Contribuir desde o início do projeto |

Badges são concedidos pelos mantenedores e exibidos no Hall da Fama. Cada badge representa **trabalho real e verificável** — algo concreto para mostrar em qualquer entrevista ou revisão de portfólio.

---

## 🚀 Roadmap

- [x] Kickoff do projeto e estrutura do repositório
- [ ] Submissão de eventos via GitHub Issues
- [ ] API REST para listagem de eventos (Spring Boot)
- [ ] Integração com PostgreSQL
- [ ] Autenticação de usuários
- [ ] Sistema de recomendação de eventos
- [ ] Plataforma web frontend
- [ ] Deploy em nuvem (AWS)
- [ ] Lançamento público 🎉

---

## 🚀 Comece Agora

<div align="center">

Faça parte da comunidade que está construindo o futuro da cena tech paulistana.

| Ação | Link |
|---|---|
| ⭐ Dê uma estrela | [Star no GitHub](https://github.com/sampatech-hub/.github/stargazers) |
| 🍴 Faça um Fork | [Fork o repositório](https://github.com/sampatech-hub/.github/fork) |
| 📩 Envie um evento | [Abrir Issue](https://github.com/sampatech-hub/.github/issues/new) |
| 🏆 Contribua com código | [Ver issues abertas](https://github.com/sampatech-hub/.github/issues) |

</div>

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](./LICENSE).

---

<div align="center">

**Feito com ❤️ pela comunidade SampaTech — São Paulo, Brasil 🇧🇷**

*Dê uma ⭐ se você acredita em construir comunidade através do open source.*

</div>

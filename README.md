<h1 align="center">
  <img alt="Ignite" src="https://res.cloudinary.com/vilmarbatista/image/upload/v1635947944/Development/Ignite/nodejs_ignite_uxnujm.png" />
</h1>

<h3 align="center">
  Ignite
</h3>

<p align="center">PIZZA.SHOP - Dashboard e lista de pedidos</p>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/vilmarsitiodigital/pizzashop-api?color=dc2627">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/vilmarsitiodigital/pizzashop-api?color=dc2627">

  <a href="https://github.com/vilmarsitiodigital/pizzashop-api/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vilmarsitiodigital/pizzashop-api?color=dc2627">
  </a>

  <a href="https://github.com/vilmarsitiodigital/pizzashop-api/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/vilmarsitiodigital/pizzashop-api?color=dc2627">
  </a>

  <a href="https://github.com/vilmarsitiodigital/pizzashop-api/blob/main/LICENSE">
    <img alt="GitHub" src="https://img.shields.io/github/license/vilmarsitiodigital/pizzashop-api?color=dc2627">
  </a>
</p>

## 📆 Sobre o projeto

Api para dashboard de pedidos estilo iFood, com magic link de autenticação, cadastro de estabelecimento, atualização de nome e descrição do usuário logado, filtros, paginação e mudança de status dos pedidos.
<br />

## 🚀 Tecnologias

Tecnologias e ferramentas utilizadas no desenvolvimento do projeto:

- [Bun](https://bun.sh/)
- [Drizzle](https://orm.drizzle.team/)
- [Elysiajs](https://elysiajs.com/)
- [Zod](https://zod.dev/)
- [React Email](https://react.email/)
- [Eslint](https://eslint.org/)

## 💻 Começando

### Requirements

**Clone o projeto e acesse a pasta**

```bash
$ git clone https://github.com/vilmarsitiodigital/pizzashop-api.git && cd pizzashop-api
```

**Siga os passos abaixo**

```bash
# Instale as dependências
$ bun i

# Criando container docker
$ docker compose up -d

# Criando váriaveis de ambiente
$ cp .env.local.example .env.local

# Criando a estrutura do banco de dados
bun migrate

# Criando dados iniciais para o banco de dados
bun seed

# Aplicação no ar
bun dev
```

## 🤔 Como contribuir

**Faça um fork deste repositório**

```bash
# Fork usando a linha de comando oficial do GitHub
# Se você não tiver a CLI do GitHub, use o site para fazer isso.

$ gh repo fork vilmarsitiodigital/pizzashop-api
```

**Siga os passos abaixo**

```bash
# Clone your fork
$ git clone your-fork-url && cd pizzashop-api

# Create a branch with your feature
$ git checkout -b my-feature

# Make the commit with your changes
$ git commit -m 'Feature: My new feature'

# Send the code to your remote branch
$ git push origin my-feature
```

Depois que sua solicitação pull for mesclada, você poderá excluir sua ramificação

## 📝 Licença

Este projeto está licenciado sob a Licença MIT - veja o [LICENSE](LICENSE) arquivo para mais detalhes.

---

Feito com 💚 por Vilmar Batista 👋 [See my linkedin](https://www.linkedin.com/in/vilmarbatista/)

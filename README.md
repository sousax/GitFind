# GitFind

Busca de usuários do GitHub em React: digite o login e veja o perfil e os repositórios públicos.

## Funcionalidades

- Consulta `https://api.github.com/users/{usuario}` e mostra avatar, nome, login e bio.
- Lista os repositórios públicos do usuário (`/users/{usuario}/repos`) com nome e descrição.

A API do GitHub é chamada sem autenticação, então vale o limite de 60 requisições por hora por IP.

## Tecnologias

- React 18 (Create React App)
- CSS puro
- API REST do GitHub

## Como rodar

```bash
npm install
npm start      # http://localhost:3000
```

Build de produção: `npm run build`.

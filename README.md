# Cloud Deploy - Docker & Render

Projeto desenvolvido para a disciplina de Computação em Nuvem e DevOps.

## Tecnologias

- Node.js 22
- TypeScript
- React
- Vite
- Docker
- Docker Compose
- PostgreSQL
- Nginx
- Docker Hub
- Render

## Estrutura

- backend/ - API Node.js
- frontend/ - Aplicação React
- docker-compose.yml - Orquestração dos contêineres

## Executar localmente

```bash
docker compose up --build -d
```

## Verificar contêineres

```bash
docker compose ps
```

## Acessar aplicação

Frontend: http://localhost:8080

Backend: http://localhost:3000

## Hospedagem

A aplicação será hospedada no Render utilizando imagens publicadas no Docker Hub.

## Autor

Ronaldo Malta
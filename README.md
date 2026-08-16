# Meu Chef Edil Digital — Fichas Técnicas e Precificação

Aplicação web para cozinhas profissionais: criação de fichas técnicas de pratos e precificação. Parte do ecossistema **Chef Edil Costa** ([gastronomiaedilcosta.com.br](https://gastronomiaedilcosta.com.br)).

## Funcionalidades

- Fichas técnicas com ingredientes, rendimento e modo de preparo
- Cálculo de custos e precificação de pratos
- Organização por arrastar e soltar (dnd-kit)
- Funciona offline — PWA com service worker
- Testes unitários dos cálculos e da persistência

## Stack

React 18 · TypeScript · Vite · shadcn/ui (Radix) · Tailwind CSS · Vitest · Docker

## Rodando localmente

```sh
npm install
npm run dev
```

## Testes

```sh
npm run test:run        # suíte completa
npm run test:coverage   # com cobertura
```

## Build

```sh
npm run build           # build de produção (Vite)
```

Também há um `Dockerfile` para build containerizado e CI configurado em `.github/workflows/ci.yml`.

## Documentação

O diretório [`docs/`](docs/) contém o plano de implementação, avaliações e guias de integração com o app principal.

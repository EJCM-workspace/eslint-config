# Pré configurações do ESLint para os projetos da EJCM

## O que inclui?

- Configuração Standard do ESLint;
- React plugin;
- Next plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Import Helpers para projetos Next.js

## Setup

1. Instale as dependências
```
npm i -D eslint @/eslint-config
```

2. Crie um arquivo `.eslintrc.json` estendendo a configuração:
```
{
  "extends": "@/eslint-config/react"
}
```
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
npm i -D eslint @ejcm/eslint-config
```

2. Crie um arquivo `.eslintrc.json` estendendo a configuração:

```
{
  "extends": "@ejcm/eslint-config/react"  //Para projetos React.js sem Framework
  "extends": "@ejcm/eslint-config/next"   //Para projetos Next.js
}
```

3. Se for usar o Visual Studio Code como IDE, adicione essas configurações no seu arquivo `settings.json` da IDE:

```
{
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.tabSize": 2,
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.addMissingImports": true
  } 
  "eslint.enable": true,
}
```

# My ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Import Helpers to Next.js projects

## Setup

1. Install the dependencies
```
npm i -D eslint @brunopavese/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@brunopavese/eslint-config/react"
}
```
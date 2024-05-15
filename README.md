# React + Vite + ESLint + Prettier

This template provides a minimal setup to get React working in Vite with HMR and some ESLint/Prettier configurations.

- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
- [ESLint](https://eslint.org/docs/v8.x/) with [flat configuration](https://eslint.org/docs/v8.x/use/configure/migration-guide)
  - ESLint plugins:
    - [eslint-plugin-react](https://www.npmjs.com/package/eslint-plugin-react)
    - [eslint-plugin-react-hooks](https://www.npmjs.com/package/eslint-plugin-react-hooks)
    - [eslint-plugin-react-refresh](https://www.npmjs.com/package/eslint-plugin-react-refresh)
    - [eslint-config-prettier](https://www.npmjs.com/package/eslint-config-prettier)
    - [eslint-plugin-prettier](https://www.npmjs.com/package/eslint-plugin-prettier)
    - [eslint-plugin-perfectionist](https://eslint-plugin-perfectionist.azat.io/guide/introduction)
- [Prettier](https://prettier.io/docs/en/)

## Requirements

- [Node.js](https://nodejs.org/en) version 18+, 20+ (tested with Node.js v20.13.1 and npm 10.5.2)

Run the application with the following commands:

```bash
npm install
npm run dev
```

## VSCode settings

```json
{
  "eslint.useFlatConfig": true,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

# React Mallows Bolierplate

React Mallows Boilerplate is a a React/TypeScript template for Vite with a set of features that will help you start your development with ease, like Husky, Commitlint, Stylelint, and more.

## How to install

```shell
npx degit pavelkeyzik/react-mallows-boilerplate#main my-project
cd my-project

npm install
npm run dev
```

## Features

- [x] - ESLint
- [x] - Stylelint (CSS, SCSS)
- [x] - Commitlint (conventional commits)
- [x] - Prettier
- [x] - Husky
- [x] - Lint-staged
- [x] - SVG support
- [x] - VSCode suggested extensions

## VSCode Settings

It's up to you how to configure them, but here's what I use:

```json
{
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll": "always"
  },
  "prettier.requireConfig": true,
  "stylelint.validate": ["css", "scss"]
}
```

# Vue 3 Playground Template

My simple template to start Vue3 new projects.

## How to use

Use the command to [`giget`][giget] download the latest commit. You can include the `--install` flag to install dependencies after cloning.

```sh
npx giget gh:ralacerda/vue3-playground-template new-project-name

# Or
npx giget --install gh:ralacerda/vue3-playground-template new-project-name
```

Install the dependencies

```
pnpm i
```

Run the dev server

```
pnpm dev
```

## What this template includes

- Vue3
- Typescript
- Vite with the following plugins:
    - unplugin-auto-import
    - unplugin-vue-components
    - unplugin-icons (with mdi icon set)
    - vite-plugin-vue-devtools
- Vitest and Vue Test Utils
- Vue Router
- Pinia
- Vueuse (only core package)
- SASS
- Prettier
- ESLint

## Packages that I might include:

- vueuse/motion
- unplugin-turbo-console

[giget]: tps://pinia.vuejs.org/https://github.com/unjs/giget
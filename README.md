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

- [Vue3][vue]
- [Typescript][typescript]
- [Vite][vite] with the following plugins:
    - [unplugin-auto-import][auto-import]
    - [unplugin-vue-components][vue-componentes]
    - [unplugin-icons][icons] ([with mdi icon set][mdi-icon-set])
    - [vite-plugin-vue-devtools][devtools]
- [Vitest][vitest] and [Vue Test Utils][vue-test-utils]
- [Vue Router][vue-router]
- [Pinia][pinia]
- [Vueuse (only core package)][vueuse]
- [SASS][sass]
- [Prettier][prettier]
- [ESLint][eslint]

## Packages that I might include:

- vueuse/motion
- unplugin-turbo-console

[giget]: tps://pinia.vuejs.org/https://github.com/unjs/giget
[vue]: https://vuejs.org/
[typescript]: https://www.typescriptlang.org/
[vite]: https://vitejs.dev/
[auto-import]: https://github.com/unplugin/unplugin-auto-import
[vue-componentes]: https://github.com/unplugin/unplugin-vue-components
[icons]: https://github.com/antfu/unplugin-icons
[mdi-icon-set]: https://icon-sets.iconify.design/mdi/
[devtools]: https://devtools-next.vuejs.org/
[vitest]: https://vitest.dev/
[vue-test-utils]: https://test-utils.vuejs.org/
[vue-router]: https://router.vuejs.org/
[pinia]: https://pinia.vuejs.org/
[vueuse]: https://vueuse.org/
[sass]: https://sass-lang.com/
[prettier]: https://prettier.io/
[eslint]: https://eslint.org/
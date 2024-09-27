# Vue SPA Starter

This template should help get you started developing with Vue 3 in Vite.

## Stater Configuration

- [@tanstack/vue-query](https://tanstack.com/query/latest/docs/framework/vue/overview)
    - For Data Fetching
- [VueUse](https://vueuse.org/)
  - Collection of Essential Vue Composition Utilities
- [shadcn-vue](https://www.shadcn-vue.com/)
  - Collection of Essential UI Components
- [Unplugin Vue Router](https://uvr.esm.is/)
  - Typed, file-based routing for Vue 3

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

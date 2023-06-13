# @yutengjing/tsconfig

[![npm](https://img.shields.io/npm/v/@yutengjing/tsconfig-base.svg)](https://npmjs.com/package/@yutengjing/tsconfig-base) [![downloads](https://img.shields.io/npm/dw/@yutengjing/tsconfig-base)](https://npmjs.com/package/@yutengjing/tsconfig-base) [![test](https://github.com/tjx666/tsconfig/actions/workflows/test.yml/badge.svg)](https://github.com/tjx666/tsconfig/actions/workflows/test.yml)

## Config list

- [@yutengjing/tsconfig-base](https://github.com/tjx666/tsconfig/tree/main/packages/base)
- [@yutengjing/tsconfig-node](https://github.com/tjx666/tsconfig/tree/main/packages/node)
- [@yutengjing/tsconfig-vue](https://github.com/tjx666/tsconfig/tree/main/packages/vue)
- [@yutengjing/tsconfig-react](https://github.com/tjx666/tsconfig/tree/main/packages/react)

## Usage

### Install

for node user:

```bash
pnpm add -D @yutengjing/tsconfig-node

# peerDependencies
# pnpm add -D @types/node
```

for vue user:

```bash
pnpm add -D @yutengjing/tsconfig-vue

# peerDependencies
# pnpm add vue
# pnpm add -D vite
```

for react user:

```bash
pnpm add -D @yutengjing/tsconfig-react

# peerDependencies
# pnpm add -D @types/react @types/react-dom
```

### Config tsconfig.json

```json
{
  "extends": "@yutengjing/tsconfig-node/tsconfig.json"
}
```

You can check [fixtures](https://github.com/tjx666/tsconfig/tree/main/fixtures) to see how to use in real projects.

## Thanks

- [Centralized Recommendations for TSConfig bases](https://github.com/tsconfig/bases)
- [@vue/tsconfig](https://github.com/vuejs/tsconfig)

## Related

- [@yutengjing/eslint-config](https://github.com/tjx666/eslint-config/tree/main)
- [@yutengjing/prettier-config](https://github.com/tjx666/prettier-config/tree/main)

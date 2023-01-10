# `@w7it/typescript-config`

## Installation

```
npm install --save-dev @w7it/typescript-config
```

Or:

```
yarn add -D @w7it/typescript-config
```

## Usage

Just add `extends` to your `tsconfig.json`:

```json
{
  "extends": "@w7it/typescript-config/base.json",

  "include": ["src/**/*.ts", "src/types/**/*.d.ts"],
  "exclude": ["node_modules", "**/node_modules/*"]
}
```

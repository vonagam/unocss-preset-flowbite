# @vonagam/unocss-preset-flowbite

[![Package Version](https://img.shields.io/npm/v/%40vonagam/unocss-preset-flowbite)](https://www.npmjs.com/package/@vonagam/unocss-preset-flowbite)
[![License](https://img.shields.io/npm/l/%40vonagam%2Funocss-preset-flowbite)](https://github.com/vonagam/unocss-preset-flowbite/blob/master/LICENSE.md)

Flowbite preset for UnoCSS. Covers everything that Flowbite plugin for Tailwind provides plus default primary color minus charts.

## Installation

```
npm install --save-dev @vonagam/unocss-preset-flowbite
yarn add --dev @vonagam/unocss-preset-flowbite
pnpm add --save-dev @vonagam/unocss-preset-flowbite
```

## Usage

Add `presetFlowbite()` to `presets` in your unocss config:

```js
// ...
import {presetFlowbite} from '@vonagam/unocss-preset-flowbite';

export default defineConfig({
  // ...
  presets: [
    // ...
    presetFlowbite(),
  ],
});
```

# Code Snippets

Code snippets for vscode.

## Code Snippets

### Full HTML5 Tag

Support `.html` and `.vue` files. Reference link: [https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element).

### JavaScript

| Prefix | Content |
| -------: | ------- |
| `imp` | `import ... from '...'`|
| `imp` | `import '...'` |
| `imp` | `import { ... } from '...'` |
| `imp` | `import * as ... from '...'` |
| `req` | `require('...')`|
| `req` | `const ... = require('...')`|
| `mod` | `module.exports = { ... }`|
| `exp` | `export const ... = ...` |
| `exp` | `export const ... = (...) => { ... }` |
| `exp` | `export default function ...(...){ ... }` |
| `exp` | `export default class ... { ... }` |
| `exp` | `export default class ... extends ... { ... }` |
| `con` | `constructor(...) { ... }` |
| `met` | `...(...) { ... }` |
| `fore` | `....forEach(... => { ... })` |
| `forof` | `for (const ... of ...) { ... }` |
| `forin` | `for (const ... in ...) { ... }` |
| `const` | `const ... = (...) => { ... }` |
| `const` | `const { ... } = ...` |
| `const` | `const [...] = ...` |
| `seti` | `setInterval(() => { ... }, ...)` |
| `sett` | `setTimeout(() => { ... }, ...)` |
| `prom` | `return new Promise((resolve, reject) => { ... })` |
| `then` | `.then((...) => { ... ).catch((...) => { ... })` |
| `log` | `console.log(...)` |
| `log` | `console.log('... :>> ', ...)` |
| `todo` | `// TODO ...` |
| `set` | `this.setData({ ... })` |
| `bi` | `this._collect.bi('...', ...)` |
| `elk` | `this._collect.elk('...', ...)` |
| `business` | `this._collect.business('...', ...)` |
| `alert` | `Actions.Toast.alert('...')` |
| `fail` | `Actions.Toast.fail('...')` |
| `success` | `Actions.Toast.success('...')` |
| `select` | `Actions.Modal.select('...', '...', {...})` |

### Vue

| Prefix | Content |
| -------: | ------- |
| `template` | `<template><div></div></template>` |
| `script` | `<script setup></script>` |
| `script` | `<script setup lang="ts"></script>` |
| `style` | `<style scoped></style>` |
| `style` | `<style scoped lang="less"></style>` |
| `style` | `<style scoped lang="scss"></style>` |
| `v-show` | `v-show=""` |
| `v-if` | `v-if=""` |
| `v-else` | `v-else` |
| `v-else-if` | `v-else-if=""` |
| `v-for` | `v-for=(..., ...) in ..." :key="..."` |
| `ref` | `ref=""` |
| `component` | `<component :is="..."></component>` |
| `keep-alive` | `<keep-alive></keep-alive>` |
| `router-link` | `<router-link to="..."></router-link>` |
| `router-view` | `<router-view></router-view>` |

### Markdown

| Prefix | Content |
| -------: | ------- |
| `code` | `` |
| `md` | \``` md \``` |
| `bash` | \``` bash \``` |
| `html` | \``` html \``` |
| `css` | \``` css \``` |
| `js` | \``` js \``` |
| `vue` | \``` vue \``` |
| `ts` | \``` ts \``` |

## License

[MIT](./LICENSE) License © 2022 [Hongbusi](https://github.com/Hongbusi)

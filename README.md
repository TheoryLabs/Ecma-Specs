<a href="https://theorylabs.dev" target="_blank">
 <img src="https://picc.io/GUfS6PH.png" alt="TheoryLabs Logo" style="display:block;margin-left: auto;margin-right: auto;width: 35%;">
</a>

# Ecma Specs
> **ECMA**Script _(a.k.a **JavaScript**)_ language specifications as defined via official documentation. Resources include:
  - [ECMAScript® 2022 Language Specification](https://tc39.es/ecma262)
  - [MDN Web Docs (JavaScript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Installation
_`yarn` is **preferred** package manager_

```bash
yarn add @theorylabs/ecma-specs
```

## Usage
> _Supports both `import` and `require` module usage._

```js
// Using "import" statement
import EcmaSpecs from '@theorylabs/ecma-specs'

console.log(EcmaSpecs)
//=> ['Array', 'ArrayBuffer', 'Boolean', …]
```

```js
// Using "require" statement
const EcmaSpecs = require('@theorylabs/ecma-specs')

console.log(EcmaSpecs)
//=> ['Array', 'ArrayBuffer', 'Boolean', …]
```


## License

MIT © 2021 [TheoryLabs](https://TheoryLabs.dev) | Dane@TheoryLabs.dev

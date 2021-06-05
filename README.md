# Luhn Algorithm

![npm (scoped)](https://img.shields.io/npm/v/@amm834/luhn?logo=npm&style=plastic)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@amm834/luhn?logo=npm&style=plastic)
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/amm834/luhn?include_prereleases&style=plastic)
![NPM](https://img.shields.io/npm/l/@amm834/luhn?style=plastic)

![Libraries.io dependency status for latest release, scoped npm package](https://img.shields.io/librariesio/release/npm/@amm834/luhn?style=plastic)
[![Node.js Package](https://github.com/amm834/luhn/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/amm834/luhn/actions/workflows/npm-publish.yml)
![Maintenance](https://img.shields.io/maintenance/yes/2021?style=plastic)

Luhn algorithm that can validate the cc - Credit Card numbers is valid or not.

# Usage

```js
import Luhn from '@amm834/luhn';
const card_number = 4895048712071025;
const result = Luhn.validate(card_number);
console.log(result); // => true
```

# APIs

## Validation

If cc is validated by **Luhn**,it will return `true`,if not it will be `false`;

```js
/**
* @param number | string number
* @return boolean
**/
Luhn.validate(4895048712071025);
```

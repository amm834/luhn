# Luhn Algorithm

![npm](https://img.shields.io/npm/dw/@amm834/luhn?style=plastic)

![npm (scoped)](https://img.shields.io/npm/v/@amm834/luhn?logo=npm&style=plastic)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@amm834/luhn?logo=npm&style=plastic)
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/amm834/luhn?include_prereleases&style=plastic)
![NPM](https://img.shields.io/npm/l/@amm834/luhn?style=plastic)

[![@amm834/luhn](https://snyk.io/advisor/npm-package/@amm834/luhn/badge.svg)](https://snyk.io/advisor/npm-package/@amm834/luhn)
![Libraries.io dependency status for latest release, scoped npm package](https://img.shields.io/librariesio/release/npm/@amm834/luhn?style=plastic)
![Maintenance](https://img.shields.io/maintenance/yes/2021?style=plastic)

> Luhn algorithm that can validate the cc - Credit Card numbers is valid or not.

You can check and validate the credit numbers that are valid or not 👀.

# Usage

How easy it is?

```js
import Luhn from '@amm834/luhn';
const cc = 4895048712071025; // Credit Card Numbers
const result = Luhn.validate(card_number); // Vaidation Result
console.log(result); // => true
```


# Installation

### npm

```bash
npm install -D @amm834/luhn
```

### yarn

```bash
yarn add @amm834/luhn
```

# Module Style Guide

## NodeJS

```js
import Luhn from '@amm834/luhn';
// some cool stuffs ...
```

## CommonJS 

```js
const Luhn = require('amm834/luhn');
// some cool stuffs ...
```

## Browser

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>

<script src="path/to/luhn.js" type="module"></script>
<script>
    import Luhn from '@amm834/luhn'
    // some cool stuffs ...
</script>
</body>
</html>
```

## CDN Usage

Using the CDN,you don't need to download or install to your local machine but it will need internect connection.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>

<script src="link/from/cdn-links" type="module"></script>
<script>
    import Luhn from '@amm834/luhn'
    // some cool stuffs ...
</script>
</body>
</html>
```

# CDN Links

You can connect `Luhn` via -

### Unpkg

```
https://unpkg.com/@amm834/luhn@1.0.6/lib/luhn.js
```

### Jsdelivr

```
https://cdn.jsdelivr.net/npm/@amm834/luhn@1.0.6/lib/luhn.js
```

# API Documentation

[https://amm834.github.io/luhn/](https://amm834.github.io/luhn/)


# Instance Methods

#### Luhn.validate(cc)

# Validation

If card numbers are valide,it will return true.

```js
Luhn.validate(cc);
```
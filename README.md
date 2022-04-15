# prettier-config-apax

A [Prettier](https://prettier.io) configuration based on the [Airbnb JavaScript style guide](https://github.com/airbnb/javascript)

## Installation

```sh
npm install @apaxsoftware/prettier-config-apax --save-dev
```

or

```sh
yarn add @apaxsoftware/prettier-config-apax --dev
```

## Usage

Create a `.prettierrc.json` file in your project root directory with a value:

```json
"@apaxsoftware/prettier-config-apax"
```

If you need to overwrite some properties, create a `.prettierrc.js` file in your project root directory, import the configuration and export the modifications:

```javascript
module.exports = {
  ...require('prettier-config-apax'),
  printWidth: 120,
};
```

## Properties

### `printWidth`

`100` ([reference](https://github.com/airbnb/javascript#whitespace--max-len))

### `tabWidth`

`2` ([reference](https://github.com/airbnb/javascript#whitespace--spaces))

### `useTabs`

`false` ([reference](https://github.com/airbnb/javascript#whitespace--spaces))

### `semi`

`true` ([reference](https://github.com/airbnb/javascript#semicolons--required))

### `singleQuote`

`true` ([reference](https://github.com/airbnb/javascript#strings--quotes))

### `quoteProps`

`"as-needed"` ([reference](https://github.com/airbnb/javascript#objects--quoted-props))

### `jsxSingleQuote`

`false` ([reference](https://github.com/airbnb/javascript/tree/master/react#quotes))

### `trailingComma`

`"all"` ([reference](https://github.com/airbnb/javascript#commas--dangling))

### `bracketSpacing`

`true` ([reference](https://github.com/airbnb/javascript#whitespace--in-braces))

### `jsxBracketSameLine`

`false` ([reference](https://github.com/airbnb/javascript/tree/master/react#alignment))

### `arrowParens`

`"always"` ([reference](https://github.com/airbnb/javascript#arrows--one-arg-parens))

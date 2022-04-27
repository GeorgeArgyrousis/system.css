# tokens.css

Design system tokens based on CSS custom properties.

[![npm version](https://badge.fury.io/js/tokens.css.svg)](https://badge.fury.io/js/tokens.css) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Installation
##### NPM
Download from the `npm` directory:
```
npm i tokens.css
```
##### Download
Copy the contents directly from  https://github.com/GeorgeArgyrousis/tokens.css/blob/main/tokens.css

## Usage
Use the stylesheet contents under different contexts. Minified version can be found in the same directory, named `tokens.min.css`.
##### HTML
```
<link rel="stylesheet" type="text/css" href="node_modules/tokens.css/tokens.css" />
```
##### CSS Import
```
@import "node_modules/tokens.css/tokens.css";
```
## Token conventions
Tokens.css is using the kebab naming convention with lowercase characters. The first word reflects the category of the token, followed by an optional attribute denoting the sub-collection and finally the generalised value residing within. The attribute is optional when a category (Spacing, Transition & Breakpoints) has a singular sub-collection of tokens.
```
    — — category — attribute (optional) — value
```
The dash separated variables of each token uses terminology similar to CSS declarations. For example, If we are seeking specific typographic size, we can infer the variable name by the category (`font`), followed by the attribute (`size`) and a value (`16`) -matching `--font-size-16`.

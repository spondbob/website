---
id: version-7.0.0-babel-plugin-syntax-object-rest-spread
title: @babel/plugin-syntax-object-rest-spread
sidebar_label: syntax-object-rest-spread
original_id: babel-plugin-syntax-object-rest-spread
---

> #### Syntax only
>
> It's unlikely you want to use this plugin directly as it only enables Babel to parse this syntax. Instead, use [plugin-proposal-object-rest-spread](plugin-proposal-object-rest-spread.md) to _both_ parse and transform this syntax.

## Installation

```sh
npm install --save-dev @babel/plugin-syntax-object-rest-spread
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["@babel/plugin-syntax-object-rest-spread"]
}
```

### Via CLI

```sh
babel --plugins @babel/plugin-syntax-object-rest-spread script.js
```

### Via Node API

```javascript
require("@babel/core").transform("code", {
  plugins: ["@babel/plugin-syntax-object-rest-spread"]
});
```


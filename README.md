# prettier-config

[![npm version](https://badge.fury.io/js/%40flywire%2Fprettier-config.svg)](https://badge.fury.io/for/js/@flywire/prettier-config)

Flywire's base [prettier](https://prettier.io/) configuration.

## Installation

```sh
npm install --save-dev @flywire/prettier-config
```

If you don't have it installed already, also install `prettier` as a devDependency.

```sh
npm install --save-dev prettier
```

## Usage

Create a `.prettierrc.js` or `prettier.config.js` file at the root of your project that contains:

```js
module.exports = require('@flywire/prettier-config');
```

## How to publish to npm

Read npm's docs on [How to Update a Package](https://docs.npmjs.com/getting-started/publishing-npm-packages#how-to-update-a-package).

1. `npm login`
   - Make sure you're logged into Flywire's npm account with the credentials. `npm whoami` will tell you if you're already logged in.
   
2. `npm version <update_type>`
   - `update_type` can be `patch`, `minor`, or `major`. If you don't know which one to use, go read about [semantic versioning](https://docs.npmjs.com/getting-started/semantic-versioning).

3. `npm publish`
# bdrk-stylelint-config

This repository contains the baseline StyleLint configuration for [Bedrock](https://bdrk.dev/) projects that use CSS,
SCSS, or Sass.

## Referencing this Configuration

You can reference this config by installing the NPM package in your project:

```bash
npm install --save-dev @bdrk/stylelint-config
```

Then replace the contents of your `.stylelintrc.js` file with:

```js
module.exports = {
  extends: '@bdrk/stylelint-config'
};
```

You can overwrite settings defined in this configuration by specifying them in your project's `.stylelintrc.js`.

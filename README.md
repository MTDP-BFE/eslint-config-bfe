# BFE - ESLint Shareable Config

## Install

```bash
npm install --save-dev eslint-config-bfe
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the BFE JavaScript Standard Style shareable config, first run this:

```bash
npm install --save-dev eslint-config-bfe
```

Then, add this to your .eslintrc file:

```
{
  "extends": "eslint-config-bfe"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## Learn more

For the full listing of rules, editor plugins, FAQs, and more, visit the main
[BFE JavaScript Standard Style repo](https://github.com/MTDP-BFE/eslint-config-bfe/).

## License

MIT. Copyright (c).

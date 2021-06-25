# @alexanderdavide/prettier-config [![npm](https://img.shields.io/npm/v/@alexanderdavide/prettier-config?style=for-the-badge)](https://www.npmjs.com/package/@alexanderdavide/prettier-config)

This is my preferred prettier configuration as an installable node package.

## Usage

Installation f. ex. using `npm`:

```
npm install --save-dev @alexanderdavide/prettier-config
```

Add to `package.json`:

```
{
  // ...
  "prettier": "@alexanderdavide/prettier-config"
}
```

To extend or override the configuration, use `.prettierrc.js`:

```
module.exports = {
	...require("@alexanderdavide/prettier-config"),
	semi: false,
};
```

# @qgisk/prettier-config

## Install

```npm
npm i @qgisk/prettier-config
```

## Usage

In your package.json add

```json
{
  "prettier": "@company/prettier-config"
}
```

Or if you prefer a .prettierrc

```
"@qgisk/prettier-config"
```

From the prettier docs

```
Note: This method does not offer a way to extend the configuration to overwrite some properties from the shared configuration. If you need to do that, import the file in a .prettierrc.js file and export the modifications, e.g:

module.exports = {
    ...require("@company/prettier-config"),
    semi: false,
};
```

## License

[MIT](https://github.com/QGIsK/prettier-config/blob/main/LICENSE) [@QGIsK](https://github.com/qgisk)

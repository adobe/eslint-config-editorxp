# EditorXP ESlint config

[![License](https://img.shields.io/badge/license-Apache%202-blue)](https://github.com/adobe/eslint-config-editorxp/blob/master/LICENSE)
[![NPM Version](https://img.shields.io/npm/v/@adobe/eslint-config-editorxp.svg)](https://www.npmjs.com/package/@adobe/eslint-config-editorxp)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=adobe_eslint-config-editorxp&metric=alert_status)](https://sonarcloud.io/dashboard?id=adobe_eslint-config-editorxp)
[![Known Vulnerabilities](https://snyk.io/test/github/adobe/eslint-config-editorxp/badge.svg)](https://snyk.io/test/github/adobe/eslint-config-editorxp)
[![Dependencies](https://badges.renovateapi.com/github/adobe/eslint-config-editorxp)](https://app.renovatebot.com/dashboard#github/adobe/eslint-config-editorxp)

## Installation

```
# for javascript
npm install --save-dev eslint eslint-plugin-header eslint-plugin-json @adobe/eslint-config-editorxp

# for react
npm install --save-dev react eslint-plugin-react

# for angular
npm install --save-dev eslint-angular-react

# for typescript
npm install --save-dev typescript @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

# Configuration

Add entry to `packages.json`:

```
{
  "eslintConfig": {
    "root": true,
    "extends": [ "@adobe/eslint-config-editorxp/typescript" ]
  }
}
```

Available config variants:
- `@adobe/eslint-config-editorxp`
- `@adobe/eslint-config-editorxp/react`
- `@adobe/eslint-config-editorxp/angular`
- `@adobe/eslint-config-editorxp/typescript`

# Usage

```
./node_modules/.bin/eslint folder/
```

## Contributing

Contributions are welcome! Read the [Contributing Guide](CONTRIBUTING.md) for more information.

## Licensing

This project is licensed under the Apache V2 License. See [LICENSE](LICENSE) for more information.

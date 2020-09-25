# Installation

```
npm install --save-dev eslint @adobe/eslint-config-editorxp
```

# Configuration

Add entry to `packages.json`:

```
{
  {
    "eslintConfig": {
      "root": true,
      "extends": [ "@adobe/eslint-config-editorxp/typescript" ]
    }
  }
}
```

Available rules variants:
- `@adobe/eslint-config-editorxp`
- `@adobe/eslint-config-editorxp/react`
- `@adobe/eslint-config-editorxp/typescript`

# Usage

```
eslint --ext .js,.jsx .
```

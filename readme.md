# Eslint Config

This is a simple repo containing some eslint configs that I use in my projects.

## Usage

Install the package:

```bash
npm install --save-dev @gui-marc/eslint-config-backend
```

And install the peer dependencies:

```bash
npx install-peerdeps --dev @gui-marc/eslint-config-backend
```

Then add the config to your eslint config file:

```json
{
  "extends": "@gui-marc/eslint-config-backend",
  "parserOptions": {
    "project": "./tsconfig.json" // the path to your tsconfig.json file
  }
}
```

Then add this config to your `.prettierrc` file:

```json
{
    "trailingComma": "none",
    "semi": true,
    "singleQuote": true
}
```
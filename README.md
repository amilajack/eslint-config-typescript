## Installation
```bash
npm install --save-dev eslint-config-typescript
```

## Usage
In your `.eslintrc`, add the following config:
```json
{
  "extends": "typescript"
}
```

If you want to extend multiple eslint configs:
```json
{
  "extends": [
    "typescript",
    "airbnb"
  ]
}
```

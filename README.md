# Prettier-config

A prettier config for my ng projects

# Install

install the package
`❯ npm i github:hellsgit/eslint-prettier-config`

## Config

Create .eslintrc.json in root folder and paste object below into it.

```JSON
{
  "root": true,
  "ignorePatterns": ["projects/**/*"],
  "overrides": [
    {
      "files": ["*.ts"],
      "extends": ["@hellsgit/eslint-config/typescript"]
    },
    {
      "files": ["*.html"],
      "extends": ["@hellsgit/eslint-config/html"]
    }
  ]
}
```

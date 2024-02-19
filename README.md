# Prettier-config

A prettier config for my ng projects

# Setup

install the package

## Config

If needed Create .eslintrc.json
In the .eslintrc.json file, replace all “extends” entries with these two:

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

[The Educative Team (10/2018) - The 7 Most Important Software Design Patterns](https://learningdaily.dev/the-7-most-important-software-design-patterns-d60e546afb0e)

1. Singleton
2. Factory
3. Strategy
4. Observer
5. Builder
6. Adapter
7. State

[Alex Hyett (09/2023) - 5 Design Patterns That Are ACTUALLY Used By Developers](https://www.alexhyett.com/design-patterns/)

1. Strategy
2. Decorator - open to extension closed to modification
3. Observer
4. Singleton
5. Facade

Adapter
Builder
Factory
State

# @chrisaguilar/babelrc

## Usage

`$ yarn add -D @chrisaguilar/babelrc`

Then, in `package.json`:
```json
{
  "name": "some_great_package",
  "version": "1.0.0",
  "...": "...",
  "babel": {
    "extends": "@chrisaguilar/babelrc",
    "presets": ["..."],
    "plugins": ["..."]
  }
}
```

Or, in `.babelrc`:
```json
{
  "extends": "@chrisaguilar/babelrc",
  "presets": ["..."],
  "plugins": ["..."]
}
```

## License
MIT

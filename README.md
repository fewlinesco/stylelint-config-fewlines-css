# styleint-config-fewlines-css

Disclaimer: this package is made for our internal usage and is only open source for convenience so we might not consider _Pull Requests_ or _Issues_.

Shareable config for Stylelint used by Fewlines

## Usage

This package is meant to be used with `@fewlines/front-scripts`, if you do, you only have to install this one package:

```shell
yarn add -D @fewlines/front-scripts
```

Then add these line to your `package.json`:

```json
"stylelint": {
	"extends": "fewlines-css"
}
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

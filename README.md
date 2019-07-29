# styleint-config-fewlines-css

Disclaimer: this package is made internally and is open source for convenience: feel free to use it and suggest amelioration but note that we reserve the right to not think it good for us.

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

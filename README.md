# eslint-config-xo-react-space [![Build Status](https://travis-ci.org/akameco/eslint-config-xo-react-space.svg?branch=master)](https://travis-ci.org/akameco/eslint-config-xo-react-space)

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html) for React with 2 space indent to be used with [eslint-config-xo](https://github.com/sindresorhus/eslint-config-xo)

## Install

```
$ npm install --save-dev eslint-config-xo eslint-config-xo-react-space eslint-plugin-react
```


## Usage

Add some ESLint config to your `package.json`:

```json
{
	"name": "my-awesome-project",
	"eslintConfig": {
		"extends": ["xo", "xo-react-space"]
	}
}
```

Or to `.eslintrc`:

```json
{
	"extends": ["xo", "xo-react-space"]
}
```

You can also mix it with a sub-config:

```json
{
	"extends": ["xo/esnext", "xo-react-space"]
}
```


## Tip

### Use with XO

```
$ npm install --save-dev eslint-config-xo-react-space eslint-plugin-react
```

```json
{
	"name": "my-awesome-project",
	"xo": {
		"extends": "xo-react-space"
	}
}
```


## Related

- [eslint-config-xo](https://github.com/sindresorhus/eslint-config-xo) - ESLint shareable config for XO
- [eslint-config-xo-space](https://github.com/sindresorhus/eslint-config-xo-space) - ESLint shareable config for XO with 2-space indent
- [eslint-config-xo-react](https://github.com/sindresorhus/eslint-config-xo-react) -  ESLint shareable config for React to be used with the above


## License

MIT

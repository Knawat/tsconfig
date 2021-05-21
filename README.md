# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```
$ npm install --save-dev @knawat/tsconfig
```

## Usage

`tsconfig.json`

```json
{
	"extends": "@knawat/tsconfig",
	"compilerOptions": {
		"outDir": "dist"
	}
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
	"extends": "@knawat/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "ES2021"
	}
}
```

# eslint-plugin-ascii
ESLint plugin to detect non-ascii characters in JavaScript source code.

[![Build Status](https://travis-ci.org/jsus1/eslint-plugin-ascii.svg?branch=master)](https://travis-ci.org/jsus1/eslint-plugin-ascii)

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-ascii`:

```
$ npm install eslint-plugin-ascii --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-ascii` globally.

## Usage

Add `ascii` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "ascii"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "ascii/valid-name": 2
    }
}
```

[![NPM](https://nodei.co/npm/eslint-plugin-ascii.png)](https://nodei.co/npm/eslint-plugin-ascii/)

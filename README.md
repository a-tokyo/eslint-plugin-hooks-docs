# eslint-plugin-react-hooks-docs

🚨 Eslint plugin to enforce react hooks documentation.

<br>

<a href="https://npmjs.com/package/eslint-plugin-react-hooks-docs">
  <img src="https://img.shields.io/npm/v/eslint-plugin-react-hooks-docs.svg"></img>
  <img src="https://img.shields.io/npm/dt/eslint-plugin-react-hooks-docs.svg"></img>
</a>
<a href="https://twitter.com/intent/follow?screen_name=ahmad_tokyo"><img src="https://img.shields.io/twitter/follow/ahmad_tokyo.svg?label=Follow%20@ahmad_tokyo" alt="Follow @ahmad_tokyo"></img></a>

<br>

## Installation

```bash
npm i eslint eslint-plugin-react-hooks-docs --save-dev
```
OR
```bash
yarn add -D eslint eslint-plugin-react-hooks-docs --save-dev
```

## Usage

Add `react-hooks-docs` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": ["react-hooks-docs"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "react-hooks-docs/docs": [
      2,
      {
        "skipDeclarations": true,
        "skipHooks": [
          "useCustomEffect"
        ]
      }
    ]
  }
}
```

<p align="center">
  <sub>Built with ❤︎ by <a href="https://ahmedtokyo.com">Ahmed Tokyo</a>
  <br/>
</p>

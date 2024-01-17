<h1 align="center"> eslint-plugin-react-hooks-docs </h1>

<p align="center">
  <a href="https://github.com/a-tokyo/eslint-plugin-react-hooks-docs/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/a-tokyo/eslint-plugin-react-hooks-docs?color=0d1117&style=for-the-badge&colorA=1C1D27">
  </a>
  <a href="https://github.com/a-tokyo/eslint-plugin-react-hooks-docs/network">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/a-tokyo/eslint-plugin-react-hooks-docs?color=0d1117&style=for-the-badge&colorA=1C1D27">
  </a>
  <a href="https://github.com/a-tokyo/eslint-plugin-react-hooks-docs/issues">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/a-tokyo/eslint-plugin-react-hooks-docs?style=for-the-badge&color=0d1117&colorA=1C1D27">
  </a>
  <a href="httdivs://github.com/a-tokyo/eslint-plugin-react-hooks-docs/blob/develop/LICENSE">
    <img alt="GitHub license" src="https://img.shields.io/github/license/a-tokyo/eslint-plugin-react-hooks-docs?color=0d1117&style=for-the-badge&colorA=1C1D27" />
  </a>
  <a href="https://www.npmjs.com/package/eslint-plugin-react-hooks-docs">
    <img alt="NPM" src="https://img.shields.io/npm/dt/eslint-plugin-react-hooks-docs?color=0d1117&style=for-the-badge&colorA=1C1D27" />
  </a>
</p>

<h3 align="center"> 🚨 Eslint plugin to enforce react hooks documentation. </h3>

<p align="center">
  <sub>Built with ❤︎ by <a href="https://ahmedtokyo.com">Ahmed Tokyo</a>
  <br/>
</p>

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

<div align="center">
  <img src="https://gist.githubusercontent.com/0-vortex/3acb60674856c437c86bee683d96515b/raw/fab74e1934e5a8686a3190f4d53606bb11da4d96/logo.png" width="400">

# @hypercubesphere/conventional-commit

> Never miss a conventional commit with [**commitizen**](https://github.com/commitizen/cz-cli) running on [**npx**](https://www.npmjs.com/package/npx).

[![Commits](https://img.shields.io/github/commit-activity/w/open-sauced/conventional-commit?style=flat)](https://github.com/open-sauced/conventional-commit/pulse)
[![Issues](https://img.shields.io/github/issues/open-sauced/conventional-commit.svg?style=flat)](https://github.com/open-sauced/conventional-commit/issues)
[![Releases](https://img.shields.io/github/v/release/open-sauced/conventional-commit.svg?style=flat)](https://github.com/open-sauced/conventional-commit/releases)

</div>

## 📦 Install

This package is binary and doesn't require installation however you can add it to your repository as a `devDependency`:

```shell
npm install --save-dev @hypercubesphere/conventional-commit
```

## 🚀 Usage

All you have to do is run the script next to your `package.json`:

```shell
npx @hypercubesphere/conventional-commit
# or
npx conventional-commit
```

## 🔧 Configuration

The most common use case for this package is to run it instead of the `git commit` command inside your `npm` scripts:

```json
{
  "scripts": {
    "push": "npx @hypercubesphere/conventional-commit"
  }
}
```

or

```json
{
  "scripts": {
    "push": "npx conventional-commit"
  }
}
```

If you want to ensure local-only usage:

```json
{
  "scripts": {
    "push": "conventional-commit"
  }
}
```

## 🤝 Contributing

If you decide to fix a bug, make sure to use the conventional commit available at:

```shell
npm run push
```

## ⚖️ LICENSE

MIT © [TED (Teodor-Eugen Dutulescu) Vortex](./LICENSE)

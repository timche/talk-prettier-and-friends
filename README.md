# Talk: Prettier and Friends

> Slides and examples from my talk at HannoverJS in November 2017

## Slides

http://slides.com/timche/formatting-code-with-prettier-and-friends

## VOD

[![YouTube](https://img.youtube.com/vi/qOnTh7xwvpY/0.jpg)](https://www.youtube.com/watch?v=qOnTh7xwvpY)

## Examples Usage

This repository contains two branches `master` and `pre-commit-hook` demonstrating two ways of formatting files in a `examples` folder with [Prettier](https://prettier.io). Checkout `package.json` on both branches for more details.

### `master`

Running Prettier manually.

```sh
# Install dependencies
npm install

# Run Prettier
npm run prettier
```

### `pre-commit-hook`

Running [Prettier](https://github.com/prettier/prettier) as a [Git `pre-commit` hook](https://git-scm.com/book/gr/v2/Customizing-Git-Git-Hooks) with [Husky](https://github.com/typicode/husky) and [lint-staged](https://github.com/okonet/lint-staged).

```sh
# Instal dependencies
npm install

# Add `examples/` from `master`
git checkout master examples

# Commit
git commit -m 'add examples'
```

# Talk: Prettier and Friends

> Slides and examples from my talk at HannoverJS in November 2017

## Slides

http://slides.com/timche/formatting-code-with-prettier-and-friends

## Examples Usage

This repository contains two branches `master` and `pre-commit-hook` demonstrating two ways of using [Prettier](https://prettier.io) in a `examples` folder.

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

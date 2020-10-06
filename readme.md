# template-typescript-library

A starter template configured for Typescript based node projects.
I use these tools for librarires all the time now, so I've made a template for convenience.

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Setup](#setup)
- [Tools](#tools)
  - [`yarn`](#yarn)
  - [`typescript`](#typescript)
  - [`prettier`](#prettier)
  - [`eslint`](#eslint)
  - [`lint-staged`](#lint-staged)
  - [`husky`](#husky)
  - [`commitlint`](#commitlint)
  - [`commitizen`](#commitizen)
  - [`semantic-release`](#semantic-release)
  - [`jest`](#jest)
  - [Github Actions](#github-actions)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Setup

Once you've cloned this template and downloaded it to your local machine, you'll have a few things to do before it will be truly yours.

| File                                       | Action                                           |
| :----------------------------------------- | :----------------------------------------------- |
| **`packagejson.name`**                     | Change to the name that will be consumed by NPM. |
| **`packagejson.repository.url`**           | Change to your git repository URL.               |
| **`.github/workflows/main.yaml.template`** | Rename `main.yaml.template` to `main.yaml`.      |

## Tools

### `yarn`

### `typescript`

The build script runs in parallel thanks to `npm-run-all --parallel`.

### `prettier`

### `eslint`

### `lint-staged`

### `husky`

### `commitlint`

### `commitizen`

### `semantic-release`

### `jest`

### Github Actions

# <package-name>

When asking users to install your package, they need to run the following:

```
echo "@waynevanson:registry=https://npm.pkg.github.com" >> .npmrc
yarn add @waynevanson/<package-name>
```

A starter template configured for Typescript based node projects.
I use these tools for librarires all the time now, so I've made a template for convenience.

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

## Setup

Once you've cloned this template and downloaded it to your local machine, you'll have a few things to change before it will be truly yours.

| File                             | Action                                           |
| :------------------------------- | :----------------------------------------------- |
| **`packagejson.name`**           | Change to the name that will be consumed by NPM. |
| **`packagejson.repository.url`** | Change to your git repository URL.               |

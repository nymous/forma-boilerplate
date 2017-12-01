Presentation boilerplate
========================

A small boilerplate to create a presentation using [remark.js](https://remarkjs.com/)

## Usage

Clone this project, delete the `.git` folder, and start from a fresh boilerplate!

⚠️
Run `npm run update:remark` to download latest version of Remark before working.
⚠️

Write the `.md` in src, it will be included in the `src/index.html`.

There is a `gulp watch` to run browsersync with auto reload on change.

`npm run build` compiles everything, and copies assets to `dist/assets`.

Deploy to gh-pages with `npm run deploy`.

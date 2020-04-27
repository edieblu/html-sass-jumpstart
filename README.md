# HTML / SASS Jumpstart

> node-sass powered, includes stylelint and prettier, and autoprefix upon build. develop script includes hot-reload via browsersync.

## Getting Started

Run a find/replace for `tdbc` to update to your preferred prefix (or adjust stylelint settings).

You can customize the `theme` Sass directly, or place overrides to variables at the top of the main `style.scss` file before the `theme` file is imported.

Then continue with the `develop` script and build something rad :)

## Development Scripts

**`npm run develop`**

> Serve with hot reload at localhost:1337

**`npm run build`**

> Generate minified, autoprefixed CSS for production

Use this as the "Publish command" if needed by hosting such as Netlify.

**`npm run serve`**

> Serve latest build files at localhost:1337

## Linting

Linting is provided by [Stylelint](https://stylelint.io/) and rules are extended from [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) and [prettier-stylelint](https://github.com/hugomrdias/prettier-stylelint)

### Lint Script

**`npm run lint`**

> Run stylelint and review errors in terminal

**`npm run lint:fix`**

> Run stylelint with the fix flag to attempt to resolve found errors

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/lit-place-input) [![npm version](https://badge.fury.io/js/whatsapp-button.svg)](https://badge.fury.io/js/lit-place-input)

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

# \<lit-place-input>

This webcomponent follows the [open-wc](https://github.com/open-wc/open-wc) recommendation.

## Installation
```bash
npm i lit-place-input
```

## Usage
```html
<script type="module">
  import 'lit-place-input/lit-place-input.js';
</script>

<lit-place-input></lit-place-input>
```

## Linting with ESLint, Prettier, and Types
To scan the project for linting errors, run
```bash
npm run lint
```

You can lint with ESLint and Prettier individually as well
```bash
npm run lint:eslint
```
```bash
npm run lint:prettier
```

To automatically fix many linting errors, run
```bash
npm run format
```

You can format using ESLint and Prettier individually as well
```bash
npm run format:eslint
```
```bash
npm run format:prettier
```

## Testing with Karma
To run the suite of karma tests, run
```bash
npm run test
```
or to run them in compatibility mode for legacy browsers
```bash
npm run test:compatibility
```

To run the tests in watch mode (for <abbr title="test driven development">TDD</abbr>, for example), run

```bash
npm run test:watch
```
or
```bash
npm run test:compatibility
```

## Testing with Karma via BrowserStack
To run the suite of karma tests in BrowserStack, run
```bash
npm run test:bs
```

## Managing Test Snapshots
You can manage the test snapshots using
```bash
npm run test:update-snapshots
```
or
```bash
npm run test:prune-snapshots
```

## Demoing with Storybook
To run a local instance of Storybook for your component, run
```bash
npm run storybook
```

To build a production version of Storybook, run
```bash
npm run storybook:build
```


## Local Demo with `es-dev-server`
```bash
npm start
```
To run a local development server that serves the basic demo located in `demo/index.html`

```bash
npm start:compatibility
```
To run a local development server in compatibility mode for older browsers that serves the basic demo located in `demo/index.html`

[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg
[buymeacoffee]: https://www.buymeacoffee.com/0lUd5Y3
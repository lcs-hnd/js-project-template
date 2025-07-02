# Modern JavaScript Template

[![Repo size](https://img.shields.io/github/repo-size/lcs-hnd/js-project-template)](https://github.com/lcs-hnd/js-project-template)
[![License](https://img.shields.io/github/license/lcs-hnd/js-project-template)](https://github.com/lcs-hnd/js-project-template)
[![Last commit](https://img.shields.io/github/last-commit/lcs-hnd/js-project-template)](https://github.com/lcs-hnd/js-project-template)

> A minimal boilerplate for modern vanilla JavaScript development. Includes Webpack 5 for bundling, a live dev server, ESLint for code quality, Prettier for formatting, and Stylelint for CSS.

---

## Features

- **Module Bundling**: Pre-configured with Webpack 5 for efficient asset bundling.
- **Modern JavaScript**: Use the latest JavaScript features with Babel transpilation.
- **Code Quality**: Enforce consistent code style with ESLint and Prettier.
- **Style Management**: Lint and auto-prefix CSS with Stylelint and PostCSS.
- **Live Development**: A ready-to-use Webpack dev server with hot reload functionality.

---

## Getting Started

To get a local copy up and running, follow these simple steps.

1.  Clone the repository:
    ```bash
    git clone [https://github.com/lcs-hnd/js-project-template](https://github.com/lcs-hnd/js-project-template)
    ```
2.  Navigate into the project directory:
    ```bash
    cd js-project-template
    ```
3.  Install NPM packages:
    ```bash
    npm install
    ```
4.  Start the development server:
    ```bash
    npm start
    ```

---

## Available Scripts

In the project directory, you can run the following commands:

- `npm start` or `npm run dev`
  - Runs the app in development mode with a live server.

- `npm run build`
  - Builds the app for production to the `dist` folder.

- `npm run format`
  - Formats all project files with Prettier.

- `npm run lint:js`
  - Lints and attempts to automatically fix JavaScript files.

- `npm run lint:css`
  - Lints and attempts to automatically fix CSS files.

- `npm run fix:all`
  - Runs all formatting and lint-fixing commands in sequence.

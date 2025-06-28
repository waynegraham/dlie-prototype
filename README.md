# DLIE Prototype

This is a prototype for the Digital Library of the Middle East (DLME). It is built with [Eleventy](https://www.11ty.dev/) and [Tailwind CSS](https://tailwindcss.com/).

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [pnpm](https://pnpm.io/)

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/waynegraham/dlie-prototype.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd dlie-prototype
    ```
3.  Install the dependencies:
    ```bash
    pnpm install
    ```

## Usage

### Development

To start the development server, run the following command:

```bash
pnpm start
```

This will start the Eleventy development server and watch for changes to the files. It will also start the PostCSS watcher to rebuild the CSS when changes are made.

### Building

To build the project for production, run the following command:

```bash
pnpm build
```

This will create a `_site` directory with the production-ready files.

## Linting and Formatting

This project uses [ESLint](https://eslint.org/) for JavaScript linting, [Stylelint](https://stylelint.io/) for CSS linting, and [Prettier](https://prettier.io/) for code formatting.

To run the linters, use the following commands:

- **JavaScript:** `pnpm lint:js`
- **CSS:** `pnpm lint:css`
- **HTML:** `pnpm lint:html`
- **All:** `pnpm lint`

To format the code, run the following command:

```bash
pnpm format
```

To check for formatting issues, run:

```bash
pnpm format:check
```

## Running Tests

This project uses [Jest](https://jestjs.io/) for testing. To run the tests, use the following command:

```bash
pnpm test
```

## Dependencies

### Production Dependencies

- [@11ty/eleventy-navigation](https://www.11ty.dev/docs/plugins/navigation/)
- [@11tyrocks/eleventy-plugin-emoji-readtime](https://github.com/5t3ph/eleventy-plugin-emoji-readtime)
- [@material-tailwind/html](https://www.material-tailwind.com/)
- [clean-css](https://github.com/clean-css/clean-css)
- [current-git-branch](https://github.com/sindresorhus/current-git-branch)
- [eleventy-plugin-hubspot](https://github.com/hubspot/eleventy-plugin-hubspot)
- [flowbite](https://flowbite.com/)
- [luxon](https://moment.github.io/luxon/)

### Development Dependencies

- [@11ty/eleventy](https://www.11ty.dev/)
- [@11ty/eleventy-img](https://www.11ty.dev/docs/plugins/image/)
- [autoprefixer](https://github.com/postcss/autoprefixer)
- [cross-env](https://github.com/kentcdodds/cross-env)
- [cssnano](https://cssnano.co/)
- [eslint](https://eslint.org/)
- [html-minifier-terser](https://github.com/terser/html-minifier-terser)
- [html-validate](https://html-validate.org/)
- [jest](https://jestjs.io/)
- [jest-axe](https://github.com/nickcolley/jest-axe)
- [jest-environment-jsdom](https://github.com/jest-community/jest-environment-jsdom)
- [npm-run-all](https://github.com/mysticatea/npm-run-all)
- [postcss](https://postcss.org/)
- [postcss-cli](https://github.com/postcss/postcss-cli)
- [postcss-import](https://github.com/postcss/postcss-import)
- [prettier](https://prettier.io/)
- [rimraf](https://github.com/isaacs/rimraf)
- [stylelint](https://stylelint.io/)
- [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard)
- [stylelint-config-tailwindcss](https://github.com/intellicode/stylelint-config-tailwindcss)
- [tailwindcss](https://tailwindcss.com/)

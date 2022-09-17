Web Application Template
========================

Template for creating a web application (ie runs in the browser, intended to be served by a
web server (nginx, apache, etc) using the following:

- Node
- Typescript
- Webpack
- React
- Redux
- Eslint

Only standard npm configuration is in `package.json`. All other tools use standalone configuration
files (typescript, webpack, eslint, etc.).

Use the Makefile targets for linting (`lint`), building (`build`), and packing (`pack`).

Running `make` runs the default `help` target, displaying help about the make targets available.


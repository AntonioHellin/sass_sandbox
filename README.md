# sass-workflow-sandbox

A development environment and hands-on learning sandbox demonstrating modern Sass/SCSS workflows, mixins, nesting, partials, and live compilation.

## Project Overview

`sass-workflow-sandbox` is an educational sandbox for experimenting with Syntactically Awesome Style Sheets (Sass/SCSS). The project explores modular SCSS structuring, variable definitions, mixin functions, inheritance via `@extend`, and build automation using `node-sass`.

## Features

- **Modular SCSS Architecture**: Clean partials hierarchy (`_variables.scss`, `main.scss`).
- **Live SCSS Watch Script**: Configured npm scripts watching source files and automatically compiling output to `dist/css/`.
- **Reusable Mixins & Variables**: Centralized design tokens (colors, font families, break points) and reusable utility mixins.

## Prerequisites

- Node.js (version 14.x or newer).
- npm (Node Package Manager).

## Installation/Build

1. Clone the repository:
   ```bash
   git clone https://github.com/AntonioHellin/sass_sandbox.git
   cd sass_sandbox
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the automated Sass compilation script:
   ```bash
   npm run sass
   ```

## Usage

1. Inspect or modify files in the `scss/` directory.
2. The npm watch task automatically processes and compiles changes to `dist/css/main.css`.
3. Open `dist/index.html` in your browser to inspect applied styles.

## License

This project is licensed under the [ISC License](LICENSE).

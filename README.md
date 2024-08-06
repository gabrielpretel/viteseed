# ViteSeed

Plant the seed of your project with ViteSeed, a fast and solid foundation for your development.

## Description

ViteSeed is a starter template designed to help you kickstart your project with Vite and TypeScript. It comes with pre-configured settings and essential plugins to ensure a smooth development experience.

## Features

- **Vite**: Blazing fast build tool.
- **TypeScript**: Strongly typed JavaScript.
- **SCSS**: CSS preprocessor for styling.
- **Type Checking**: Ensures code quality with `vite-plugin-checker`.
- **Legacy Browser Support**: Compatibility with older browsers using `@vitejs/plugin-legacy`.

## Getting Started

### Prerequisites

Make sure you have Node.js and npm installed. You can download them from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/gabrielpretel/viteseed.git
   ```

2. Navigate to the project directory:

   ```bash
   cd viteseed
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

### Scripts

- **Start Development Server**:

  ```bash
  npm start
  ```

  This will start the Vite development server on port 1080.

- **Build for Production**:

  ```bash
  npm run build
  ```

  This will create an optimized build of your project in the `dist` directory.

- **Preview Production Build**:

  ```bash
  npm run preview
  ```

  This will start a local server to preview the production build on port 1081.

- **Type Check**:

  ```bash
  npm run type-check
  ```

  This will run TypeScript's type checker without emitting any files.

## Project Structure

- `src/`: Source code directory.

  - `index.ts`: Main entry point.
  - `css/`: Stylesheets directory.

- `public/`: Public assets directory.

  - `index.html`: HTML template.

- `vite.config.ts`: Vite configuration file.

- `tsconfig.json`: TypeScript configuration file.

## Browser compatibility

To ensure compatibility with older browsers, ViteSeed uses the @vitejs/plugin-legacy plugin. This plugin adds support for legacy browsers by transpiling the necessary JavaScript code.

## Contributing

Contributions are welcome! Please create an issue or submit a pull request to the repository.

## License

This project is licensed under the ISC License.

## Author

Gabriel Pretel

## Links

- [Repository](https://github.com/gabrielpretel/viteseed)
- [Issues](https://github.com/gabrielpretel/viteseed/issues)

# Node.js + TypeScript Boilerplate 🚀

![Node.js](https://img.shields.io/badge/Node.js-4D8C2D?style=flat&logo=node.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/Prettier-FF8B00?style=flat&logo=prettier&logoColor=white) ![Tsup](https://img.shields.io/badge/tsup-000000?style=flat&logo=typescript&logoColor=white)

Welcome to the **Node.js + TypeScript Boilerplate**! This repository provides a clean and minimal setup for building applications using Node.js and TypeScript. It includes essential tools such as ESLint for code quality, Prettier for code formatting, and tsup for bundling. It also supports environment variables through `.env` files.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Minimal Setup**: Quickly get started with a clean slate.
- **TypeScript Support**: Leverage the power of TypeScript for better type safety.
- **Linting**: Use ESLint to maintain code quality.
- **Formatting**: Automatically format your code with Prettier.
- **Bundling**: Use tsup for efficient bundling of your application.
- **Environment Variables**: Manage your app's configuration with `.env` support.

## Installation

To set up the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/srikanthRyali2004/node-ts-boilerplate.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd node-ts-boilerplate
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Create a `.env` file**: Copy the example file and configure your environment variables.
   ```bash
   cp .env.example .env
   ```

## Usage

To start the development server, run:

```bash
npm run dev
```

For production builds, use:

```bash
npm run build
```

You can run tests using:

```bash
npm test
```

## Project Structure

The project follows a simple structure:

```
node-ts-boilerplate/
├── src/
│   ├── index.ts
│   └── ... (other source files)
├── .env.example
├── .eslintrc.js
├── .prettierrc
├── package.json
└── tsconfig.json
```

- **src/**: Contains the source code of your application.
- **.env.example**: A template for your environment variables.
- **.eslintrc.js**: ESLint configuration file.
- **.prettierrc**: Prettier configuration file.
- **package.json**: Project metadata and dependencies.
- **tsconfig.json**: TypeScript configuration file.

## Configuration

You can customize the ESLint and Prettier configurations by modifying the respective files. Adjust the rules in `.eslintrc.js` to fit your coding style. Prettier settings can be found in `.prettierrc`.

## Scripts

The following scripts are available in this boilerplate:

- `dev`: Starts the development server with hot reloading.
- `build`: Compiles the TypeScript code into JavaScript.
- `test`: Runs the test suite.
- `lint`: Lints the code using ESLint.
- `format`: Formats the code using Prettier.

You can run any of these scripts using `npm run <script-name>`.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

Please ensure your code follows the existing style and passes all tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest releases, visit the [Releases](https://github.com/srikanthRyali2004/node-ts-boilerplate/releases) section. You can download and execute the latest version from there.

![Releases](https://img.shields.io/badge/Releases-Download%20Latest%20Version-blue?style=flat&logo=github&logoColor=white)

## Conclusion

This boilerplate provides a solid foundation for building Node.js applications with TypeScript. It includes essential tools and configurations to help you maintain code quality and improve your development workflow. 

Feel free to explore the repository, and don't hesitate to reach out if you have any questions or suggestions. Happy coding!
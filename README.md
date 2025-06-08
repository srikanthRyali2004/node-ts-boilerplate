<h1 align="center">🧱 Node.js + TypeScript Boilerplate</h1>

<p align="center">
  A simple and clean boilerplate to kickstart Node.js projects using TypeScript, with support for ESLint, Prettier, environment variables, and fast development tools.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-18.x-green?logo=node.js" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-blue?logo=typescript" />
  <img src="https://img.shields.io/badge/ESLint-enabled-purple?logo=eslint" />
  <img src="https://img.shields.io/badge/Prettier-enabled-yellow?logo=prettier" />
</p>

---

## 🚀 Features

- ✅ TypeScript (strict mode)
- ✅ Fast dev with `tsx` and `.env`
- ✅ Build with `tsup`
- ✅ ESLint + Prettier integrated
- ✅ Organized folder structure
- ✅ Ready for CLI tools, APIs, or workers

---

## 📁 Project Structure

```bash
📦 node-ts-boilerplate
├── src
│ └── server.ts         # Entry point
├── .env                # Environment variables
├── .eslintrc.json      # ESLint config
├── .prettierrc         # Prettier config
├── .gitignore
├── package.json
└── tsconfig.json
```

---

## 🛠️ Getting Started

```bash
# Clone the repository
git clone https://github.com/Gustavo-Zamai/node-ts-boilerplate.git
cd node-ts-boilerplate

# Install dependencies
npm install

# Start development server
npm run start:dev
```
## 📦 Scripts

| Script         | Description                                           |
|----------------|-------------------------------------------------------|
| `start:dev`    | Runs the project with `tsx` and loads `.env`         |
| `start:watch`  | Runs the project with hot-reload using `tsx watch`   |
| `build`        | Compiles the code using `tsup` to the `dist/` folder |
| `start:build`  | Runs the compiled app with `.env`                    |
| `lint`         | Lints all `.ts` files using ESLint                   |
| `format`       | Formats code using Prettier                          |


## 🧪 ESLint & Prettier
### Lint:

```bash
npm run lint
```
### Format:
```bash
npm run format
```

## 🔧 .env Example
```env
PORT=3000
```
## ✅ To-Do (Future Improvements)

- [ ] Add testing support with **Vitest** or **Jest**
- [ ] Add **Docker** support
- [ ] Add **Swagger** documentation for APIs
- [ ] Set up **GitHub Actions** for continuous integration (CI)
- [ ] Configure **Husky + lint-staged** for pre-commit hooks


## 📄 License
This project is licensed under the ISC License – free for personal and commercial use.

## 🙌 Contributing
Pull requests and suggestions are welcome. Let’s keep it simple and reusable!

## 👨‍💻 Author

**[Gustavo Zamai](https://github.com/Gustavo-Zamai)**

# 🚀 Angular Project Starter (AngularSetup)

This repository provides a **ready-to-use Angular starter project** designed to save developers time.  
Instead of manually setting up Angular, configuring ESLint/Prettier, and installing tools, you can simply:

```bash
git clone <repo-url>
cd AngularSetup
npm install
```

And you’re ready to start building! 🎉  

---

## ✨ Features

- ✅ Preconfigured with **Angular CLI** (v20.3.1)  
- ✅ **ESLint** for consistent code quality  
- ✅ **Prettier** for automatic code formatting  
- ✅ **Husky** with Git hooks (pre-commit checks)  
- ✅ Ready-to-use project structure  
- ✅ Faster setup → focus on coding, not configuration  

---

## ⚡ Getting Started

### 1. Clone the repository
```bash
git clone <repo-url>
cd AngularSetup
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start the development server
```bash
npm start
```

Then open your browser at **http://localhost:4200/**.  
The app will reload automatically when you make changes.  

---

## 📂 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Run the dev server (alias for `ng serve`) |
| `npm run build` | Build the project into the `dist/` folder |
| `npm run lint` | Run ESLint checks |
| `npm run format` | Format code with Prettier |
| `npm test` | Run unit tests with Karma |
| `npm run prepare` | Setup Husky hooks |

---

## 🛠 Code Quality Tools

### ESLint  
Ensures consistent coding standards and helps catch common bugs.  

### Prettier  
Automatically formats code to keep everything clean and readable.  

### Husky  
Runs Git hooks (e.g., lint checks before commits) to maintain project quality and prevent bad code from being committed.  

---

## 🏗 Code Scaffolding

Angular CLI includes scaffolding tools to speed up development. Example:  

```bash
ng generate component component-name
```

For a full list of schematics:  

```bash
ng generate --help
```

---

## ✅ Testing

### Unit tests
```bash
npm test
```

### End-to-end (e2e) tests
```bash
ng e2e
```
> Note: Angular CLI does not include an e2e framework by default. You can choose Cypress, Playwright, or Protractor.  

---

## 📘 Additional Resources

- [Angular CLI Documentation](https://angular.dev/tools/cli)  
- [ESLint](https://eslint.org/)  
- [Prettier](https://prettier.io/)  
- [Husky](https://typicode.github.io/husky/)  

---

## 📄 License

This project is licensed under the **MIT License**.  

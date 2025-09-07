# Web App Template

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)](https://sass-lang.com/)
[![PNPM](https://img.shields.io/badge/PNPM-F69220?style=flat-square&logo=pnpm&logoColor=white)](https://pnpm.io/)

A modern, lightweight web application template featuring TypeScript, Sass, and automated build processes. Perfect for quickly starting new web projects with modern development tools and best practices.

## ✨ Features

-   🚀 **TypeScript** - Type-safe JavaScript with ES2022 target
-   🎨 **Sass** - Enhanced CSS with variables, nesting, and mixins
-   📦 **PNPM** - Fast, disk space efficient package manager
-   🔄 **Live Reload** - Automatic compilation and watch mode
-   🗺️ **Source Maps** - Enhanced debugging experience
-   ⚡ **Concurrent Tasks** - Run multiple build processes simultaneously

## 🚀 Quick Start

### Prerequisites

Before you begin, ensure you have the following installed:

-   [Node.js](https://nodejs.org/) (version 16 or higher)
-   [PNPM](https://pnpm.io/) (will be installed automatically via corepack)

### Installation

#### Option 1: Clone the Repository

```bash
git clone https://github.com/Exotics-Forth/web-app-template.git
cd web-app-template
```

#### Option 2: Download as ZIP

1. Click the green "Code" button on the repository page
2. Select "Download ZIP"
3. Extract the ZIP file to your desired location
4. Open terminal/command prompt in the extracted folder

#### Option 3: Use as GitHub Template

1. Click the "Use this template" button on the repository page
2. Create a new repository based on this template
3. Clone your new repository

### Setup and Development

1. **Install dependencies and setup package manager:**

    ```bash
    npm install --global corepack@latest
    corepack use pnpm@latest
    pnpm install
    ```

2. **Start development mode:**

    ```bash
    pnpm run watch:all
    ```

    This will start both TypeScript and Sass compilation in watch mode.

3. **Open the project:**
   Open `index.html` in your browser or use a local development server like Live Server in VS Code.

## 📁 Project Structure

```
web-app-template/
├── 📄 index.html          # Main HTML file
├── 📄 script.ts           # TypeScript source file
├── 📄 script.js           # Compiled JavaScript (auto-generated)
├── 📄 script.js.map       # JavaScript source map (auto-generated)
├── 📄 style.scss          # Sass source file
├── 📄 style.css           # Compiled CSS (auto-generated)
├── 📄 style.css.map       # CSS source map (auto-generated)
├── 📄 package.json        # Project dependencies and scripts
├── 📄 tsconfig.json       # TypeScript configuration
├── 📄 pnpm-lock.yaml      # PNPM lockfile
├── 📄 .gitignore          # Git ignore rules
└── 📄 README.md           # This file
```

## 🛠️ Available Scripts

| Command               | Description                                           |
| --------------------- | ----------------------------------------------------- |
| `pnpm run ts:watch`   | Watch TypeScript files and compile on changes         |
| `pnpm run sass:watch` | Watch Sass files and compile on changes               |
| `pnpm run watch:all`  | Run both TypeScript and Sass watch modes concurrently |

## 🔧 Configuration

### TypeScript Configuration (`tsconfig.json`)

-   **Target:** ES2022
-   **Module:** ES2022
-   **Strict mode:** Enabled
-   **Source maps:** Enabled
-   **Output:** Current directory with source maps

### Package Manager

This project uses **PNPM** for faster installs and better disk space efficiency. The specific version is locked via `packageManager` field in `package.json`.

## 🎯 Usage

### Development Workflow

1. **Edit your code:**

    - Modify `script.ts` for JavaScript functionality
    - Modify `style.scss` for styling
    - Modify `index.html` for markup

2. **Automatic compilation:**

    - TypeScript files are automatically compiled to JavaScript
    - Sass files are automatically compiled to CSS
    - Source maps are generated for debugging

3. **Browser refresh:**
    - Refresh your browser to see changes
    - Or use a development server with auto-reload

### Adding Dependencies

```bash
# Add runtime dependencies
pnpm add <package-name>

# Add development dependencies
pnpm add -D <package-name>
```

### Production Build

For production deployment, you may want to:

1. Compile TypeScript: `npx tsc`
2. Compile Sass: `npx sass style.scss style.css --style=compressed`
3. Remove source maps and development files

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch:** `git checkout -b feature/amazing-feature`
3. **Make your changes**
4. **Test thoroughly**
5. **Commit your changes:** `git commit -m 'Add amazing feature'`
6. **Push to the branch:** `git push origin feature/amazing-feature`
7. **Open a Pull Request**

### Development Guidelines

-   Follow existing code style and conventions
-   Update documentation for new features
-   Test your changes thoroughly
-   Keep commits focused and atomic

## 📋 Requirements

-   **Node.js** 16.x or higher
-   **PNPM** (managed via corepack)
-   Modern web browser with ES2022 support

## 🔄 Version History

-   **v1.0.0** - Initial template with TypeScript, Sass, and PNPM support

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

-   [TypeScript](https://www.typescriptlang.org/) for type-safe JavaScript
-   [Sass](https://sass-lang.com/) for enhanced CSS capabilities
-   [PNPM](https://pnpm.io/) for efficient package management
-   [Concurrently](https://github.com/open-cli-tools/concurrently) for running parallel tasks

## 🆘 Support

If you encounter any issues or have questions:

1. **Check existing issues** in the repository
2. **Create a new issue** with detailed information
3. **Provide steps to reproduce** any bugs
4. **Include your environment details** (OS, Node.js version, etc.)

## 🚀 What's Next?

This template provides a solid foundation for web development. Consider extending it with:

-   **Bundler integration** (Webpack, Vite, Rollup)
-   **Testing framework** (Jest, Vitest, Cypress)
-   **Linting tools** (ESLint, Prettier)
-   **CSS framework** (Bootstrap, Tailwind CSS)
-   **Frontend framework** (React, Vue, Angular)
-   **Development server** with hot reload
-   **CI/CD pipeline** for automated deployment

---

**Happy coding! 🎉**

> Made with ❤️ for the web development community

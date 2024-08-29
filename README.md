# Vue + TypeScript + TailwindCSS Starter

Welcome to the **Vue + TypeScript + TailwindCSS Starter** repository! This project serves as a boilerplate for building modern web applications using Vue.js, TypeScript, and TailwindCSS. The goal is to provide a solid foundation to start your project quickly and with ease.

## Features

- **Vue 3**: The Progressive JavaScript Framework, for building user interfaces.
- **TypeScript**: Strongly-typed JavaScript to help you write safer and more maintainable code.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.
- **Vue Router**: Set up for handling complex routing needs.
- **Vuex**: Integrated for state management (optional).
- **ESLint + Prettier**: Configured for code quality and consistent formatting.
- **Vite**: Fast build tool and development server.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en/) (v14.x or later)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/hosseinvalikhani/vue-typescript-tailwind-starter.git
cd vue-typescript-tailwind-starter
npm install
```

Or if you prefer Yarn:

```bash
git clone https://github.com/hosseinvalikhani/vue-typescript-tailwind-starter.git
cd vue-typescript-tailwind-starter
yarn install
```

### Development

Start the development server:

```bash
npm run dev
```

Or with Yarn:

```bash
yarn dev
```

This will start the Vite development server, and you can view your application in the browser at `http://localhost:5173`.

## Project Structure

Here’s a brief overview of the project structure:

```bash
├── public/             # Static assets
├── src/
│   ├── assets/         # Images, fonts, etc.
│   ├── components/     # Vue components
│   ├── App.vue         # Root component
│   ├── main.ts         # Application entry point
│   ├── styles.css      # TailwindCSS configuration and custom styles
├── index.html          # ESLint configuration
├── .eslintrc.js        # ESLint configuration
├── postcss.config.js   # PostCSS configuration (for TailwindCSS)
├── tailwind.config.js  # TailwindCSS configuration
├── tsconfig.json       # TypeScript configuration
└── vite.config.ts      # Vite configuration
```

## Customization

- **TailwindCSS**: Tailwind is configured with the default setup. You can customize it by editing the `tailwind.config.js` file.
- **TypeScript**: Modify `tsconfig.json` to tailor TypeScript's behavior to your liking.
- **ESLint and Prettier**: Adjust the rules in `.eslintrc.js` and `.prettierrc` to enforce your preferred coding style.

## Acknowledgements

- [Vue.js](https://vuejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)

## Contact

For any questions or feedback, feel free to reach out at [hosseinvalikhani1@gmail.com]

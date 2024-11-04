# Astro 5.0 + React + Tailwind

<p align="center">
    <img src="https://github.com/jsdeveloperr/astro-react-tailwind/blob/main/src/assets/astro-react-tailwind.jpg" width="500" alt="Astro 5.0 React Tailwind Project" />
</p>

This project is built with **Astro** and **React**, leveraging **Tailwind CSS** for styling and TypeScript for type safety. The structure follows a modular approach with separate components, layouts, and pages to keep the code organized and maintainable.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

The main folders are as follows:

- **src**: Contains the core application code.
  - **components**: Contains reusable UI components, such as `CartList`, `Footer`, `Header`, and `Product`.
  - **layouts**: Contains layout components used to structure different pages.
  - **pages**: Includes different routes/pages of the application, such as `cart.astro`, `index.astro`, and `product.astro`.
  - **styles**: Global styles file (`global.css`) and any additional style-related configurations.
- **public**: For static assets like images, fonts, etc.
- **node_modules**: Holds project dependencies.
- **tsconfig.json**: Configuration file for TypeScript.
- **astro.config.mjs**: Configuration file for Astro.
- **tailwind.config.cjs**: Tailwind CSS configuration file.

## 🚀 Getting Started

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jsdeveloperr/astro-react-tailwind.git
   cd astro-react-tailwind
   ```

2. **Install dependencies**:
   This project uses **pnpm** for package management. If pnpm is not installed, install it globally:
   ```bash
   npm install -g pnpm
   ```
   Then, install the project dependencies:
   ```bash
   pnpm install
   ```

3. **Run the development server**:
   ```bash
   pnpm dev
   ```
   This command will start the Astro development server, and you can access the project at `http://localhost:4321`.

4. **Build the project for production**:
   ```bash
   pnpm build
   ```
   The production build files will be created in the `dist` folder.

5. **Preview the production build**:
   ```bash
   pnpm preview
   ```


## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |


## 🚀 Dependencies

The project uses the following major dependencies:

- **Astro**: Static site generator that supports various JavaScript frameworks, including React.
- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
  - **@astrojs/tailwind**: Astro integration for Tailwind CSS.
  - **@tailwindcss/aspect-ratio, forms, typography**: Tailwind plugins for additional styling utilities.
- **TypeScript**: Adds static typing to JavaScript, making the project more reliable and easier to debug.

## 🚀 Scripts

- **dev**: Runs the project in development mode using `astro dev`.
- **start**: Alias for running the project in development mode.
- **build**: Checks and builds the project using `astro check && astro build`.
- **preview**: Runs `astro preview` to see a production build.
- **astro**: Alias for running Astro commands.


## 🧞 Notes

- Ensure that **pnpm** is used consistently throughout the project to avoid issues with dependency management.
- TypeScript is enabled for type safety, so make sure all `.tsx` and `.astro` files use types effectively.
- Tailwind CSS is configured and used with plugins for aspect ratio, forms, and typography for improved styling capabilities.

## License

This project is licensed under the MIT License.
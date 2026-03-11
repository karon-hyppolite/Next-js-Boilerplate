# Boilerplate and Starter for Next JS 12+, Tailwind CSS 3 and TypeScript

<p align="center">
  <img src="public/assets/images/nextjs-starter-banner.png?raw=true" alt="Next js starter banner">
</p>

Boilerplate and Starter for Next.js, Tailwind CSS and TypeScript. Made with developer experience first: Next.js, TypeScript, ESLint, Prettier, Husky, Lint-Staged, VSCode, Netlify, PostCSS, Tailwind CSS.

Clone this project and use it to create your own Next.js project.

### Features

Developer experience first:

- Next.js for Static Site Generator
- Integrate with Tailwind CSS
- PostCSS for processing Tailwind CSS and integrated to `styled-jsx`
- Type checking with TypeScript
- Strict Mode for TypeScript and React 17
- Linter with ESLint (default NextJS, NextJS Core Web Vitals, Tailwind CSS and Airbnb configuration)
- Absolute Imports
- Code Formatter with Prettier
- Husky for Git Hooks
- Lint-staged for running linters on Git staged files
- VSCode configuration: Debug, Settings, Tasks and extension for PostCSS, ESLint, Prettier, TypeScript
- SEO metadata, JSON-LD and Open Graph tags with Next SEO
- Bundler Analyzer
- One click deployment with Vercel or Netlify (or manual deployment to any hosting services)
- Include a free minimalist theme
- Maximize lighthouse score

Built-in feature from Next.js:

- Minify HTML & CSS
- Live reload
- Cache busting

### Philosophy

- Minimal code
- SEO-friendly
- Production-ready

### Requirements

- Node.js 14+ and npm

### Getting started

Run the following command on your local environment:

```sh
git clone [repository] my-project-name
cd my-project-name
npm install
```

Then, you can run locally in development mode with live reload:

```sh
npm run dev
```

Open the local development server in your browser to see your project.

```text
.
|-- README.md                # README file
|-- next.config.js           # Next JS configuration
|-- public                   # Public folder
|   `-- assets
|       `-- images           # Image used by default template
|-- src
|   |-- layout               # Atomic layout components
|   |-- pages                # Next JS pages
|   |-- styles               # PostCSS style folder with Tailwind
|   |-- templates            # Default template
|   `-- utils                # Utility folder
|-- tailwind.config.js       # Tailwind CSS configuration
`-- tsconfig.json            # TypeScript configuration
```

### Customization

You can easily configure Next js Boilerplate. Please change the following file:

- `public/apple-touch-icon.png`, `public/favicon.ico`, `public/favicon-16x16.png` and `public/favicon-32x32.png`: your website favicon
- `src/styles/global.css`: your CSS file using Tailwind CSS
- `src/utils/AppConfig.ts`: configuration file
- `src/templates/Main.tsx`: default theme

### Deploy to production

You can see the results locally in production mode with:

```sh
npm run build
npm run start
```

The generated HTML and CSS files are minified (built-in feature from Next js). It will also remove unused CSS from Tailwind CSS.

You can create an optimized production build with:

```sh
npm run build-prod
```

All generated files are located at the `out` folder, which you can deploy with any hosting service.

### Deploy

Deploy this project to your preferred hosting provider after building the production output.

### VSCode information (optional)

If you are VSCode users, you can have a better integration with VSCode by installing the suggested extension in `.vscode/extension.json`. The starter code comes up with Settings for a seamless integration with VSCode. The Debug configuration is also provided for frontend and backend debugging experience.

Pro tip: if you need project-wide type checking with TypeScript, you can run a build with <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd> on Mac.

### Contributions

Everyone is welcome to contribute to this project. Feel free to open an issue if you have question or found a bug.
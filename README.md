# Table Session Application

TSA allows users to sit and chat at a "table".
Each "table" can be a game session or a general chat.

Roadmap:
- [x] View Static List of Tables
- [x] Navigation from Tables view to individual Table view and back
- [x] Integrate Authentication
- [ ] Integrate Persistent Data Storage
- [ ] Create a new Table
- [ ] Join an existing Table
- [ ] Start a Table Session
- [ ] End a Table Session

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/Baz-Co/table-session-app)

<details>
    <summary>💻 Technologies</summary>

- [Astro](https://astro.build/)
    - SSR
    - Auth.js
- [React](https://reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
</details>

<details>
    <summary>🗒️ Getting Started</summary>

Clone the repo to your local machine or start a "Codespace" on GitHub.

Rename and update the values in `.env.example` to `.env` and update the values to your credentials.

Development on this has been utilizing the Node/npm runtime.

```bash
# Install dependencies
npm install

# Start local dev server
npm run dev

# Build your production site to `./dist/`
npm run build

# Preview your build locally, before deploying
npm run preview
```
</details>

<details>
    <summary>🚀 Commands</summary>

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
| `npm start`            | Starts local dev server at `localhost:3000`        |
| `npm run reset`        | Deletes `node_modules` + `dist` folders and `package-lock.json` file |
</details>

<details>
    <summary>🏗️ Project Structure</summary>

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── tables/
│   │   │   ├── [tableId].astro
│   │   │   └── notFound.astro
│   │   ├── 404.astro
│   │   ├── index.astro
│   │   └── login.astro
│   └── styles/
│       └── base.css
├── package.json
├── .env
├── .gitignore
├── astro.config.mjs
├── auth.config.ts
├── package-lock.json
├── package.json
├── postcss.config.cjs
├── README.md
├── tailwind.config.cjs
└── tsconfig.json
```
</details>

<details>
    <summary>👐 Contributing</summary>
</details>

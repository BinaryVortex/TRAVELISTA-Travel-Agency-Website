# TRAVELISTA — Travel Agency Website

![Landing Page Screenshot](./Screenshot%202025-12-17%20at%2010.25.09.png)

A modern, responsive travel agency landing site built with React and TypeScript. This project implements a clean, mobile-first UI inspired by a Figma design and demonstrates component-driven development using Vite.

Demo Figma: https://www.figma.com/design/9cP2uQZw4Xwpe3T4INo7gK/Travel-Agency-Website

## Key Features

- Responsive landing page layout (desktop, tablet, mobile)
- Component-based UI built in TypeScript
- Styled with CSS and utility-friendly structure
- Fast dev experience using Vite

## Screenshot

The screenshot above shows the landing page (saved in the repository as `Screenshot 2025-12-17 at 10.25.09.png`).

## Tech Stack

- TypeScript
- React
- Vite
- CSS

## Getting started (improved)

This section gives you everything you need to run the project locally and build production artifacts.

Prerequisites

- Node.js (LTS) — recommended: 18.x or later. Check with `node -v`.
- npm (comes with Node) or yarn (optional). Check with `npm -v` or `yarn -v`.
- Optional: a modern browser (Chrome, Firefox, Safari) for testing.

1. Clone the repository

   git clone https://github.com/BinaryVortex/TRAVELISTA-Travel-Agency-Website.git
   cd TRAVELISTA-Travel-Agency-Website

2. Install dependencies

- Using npm (recommended):

  npm install

- Or using yarn:

  yarn install

3. Local development

- Start the dev server (Vite):

  npm run dev

  or with yarn:

  yarn dev

- Open the URL printed by the dev server (commonly http://localhost:5173).

4. Environment variables (optional)

This project does not require environment variables by default. If you add API keys or services later, create a `.env` file at the repository root and add them there (example `.env.local`):

  REACT_APP_API_URL=https://example.com

Be sure to add `.env` to `.gitignore` for secrets.

5. Build & preview production

- Build production bundle:

  npm run build

  or

  yarn build

- Preview the production build locally:

  npm run preview

  or

  yarn preview

6. Common scripts (check package.json if changed)

- `npm run dev` — start dev server
- `npm run build` — build production bundle
- `npm run preview` — preview production build

7. Troubleshooting

- If you see dependency errors, delete `node_modules` and reinstall:

  rm -rf node_modules package-lock.json
  npm install

- If port 5173 is already in use, either free it or run Vite on a different port:

  PORT=3000 npm run dev

- TypeScript errors: run `npm run dev` and address type errors reported in the terminal or the editor.

8. Tips

- Use an editor with TypeScript support (VS Code) for the best DX.
- Run a formatter/linter if present (add scripts for `prettier`/`eslint` as needed).

## Build for production

To build the site for production:

   npm run build

To preview a production build locally:

   npm run preview

(If these scripts are not present in package.json, run the appropriate Vite commands or add them.)

## Project structure (high level)

- src/ — application source code (components, pages, assets)
- index.html — app entry
- package.json — dependencies and scripts
- vite.config.ts — Vite configuration

## Contributing

Contributions are welcome. If you'd like to contribute:

1. Fork the repo
2. Create a feature branch (git checkout -b feature/name)
3. Make changes and commit them with clear messages
4. Open a pull request describing your changes

## Attribution

This project was built using a Figma design: https://www.figma.com/design/9cP2uQZw4Xwpe3T4INo7gK/Travel-Agency-Website

If you used any third-party assets, fonts or libraries, please list and attribute them here.

## License

Add your license here (e.g., MIT) or create a LICENSE file in the repository.

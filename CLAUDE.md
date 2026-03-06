# Project CLAUDE.md - React App

## Project Overview

React app starter template with MUI, TypeScript, Webpack, and Koa dev server. Reusable boilerplate for new React projects. Includes Inter font, React Router, and SCSS support out of the box.

## Tech Stack

- **Language:** TypeScript (ESM, `"type": "module"`)
- **Frontend:** React 18, MUI 6, Emotion, React Router 6, Inter font
- **Build:** Webpack 5 with Babel (env, react, typescript presets) + SVGR
- **Server:** Koa with koa-static (port 8080, SPA fallback to index.html)
- **Styling:** SCSS with MUI components
- **Linting:** `@mikey-pro/eslint-config-react`
- **Formatting:** Prettier via `mikey-pro/prettier`, Stylelint via `mikey-pro/stylelint`

## Commands

```bash
npm run build:dev         # Webpack dev build with watch
npm run build:prod        # Webpack production build
npm run start:client      # Start Koa dev server (ts-node server.ts, port 8080)
npm run fix               # ESLint auto-fix all files
```

## Conventions

- ESM only (`"type": "module"`)
- React source in `src/`, static assets in `public/`, Webpack outputs to `public/dist/`
- React functional components with TypeScript
- React ESLint config via `@mikey-pro/eslint-config-react`
- No test framework configured
- Conventional commits: `feat:`, `fix:`, `chore:`, etc.

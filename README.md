# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

## New Way of Creating React App

`Npx create-react-app` is deprecated.

To create a new React app with Vite, use:

```bash
npm install vite@latest
npm install create-vite@latest
npm create vite@latest
```

### Interactive Setup Example

```
C:\Users\Admin\Documents\React>npm create vite@latest

> npx
> create-vite

o  Project name:
   myfirstvitereactapp

o  Select a framework:
   React

o  Select a variant:
   JavaScript

o  Use rolldown-vite (Experimental)?:
   No

o  Install with npm and start now?
   Yes

o  Scaffolding project in C:\Users\Admin\Documents\React\myfirstvitereactapp...

o  Installing dependencies with npm...
   added 157 packages, and audited 158 packages in 20s
   33 packages are looking for funding
   run `npm fund` for details
   found 0 vulnerabilities

o  Starting dev server...

> myfirstvitereactapp@0.0.0 dev
> vite

VITE v7.2.4  ready in 802 ms

➜  Local:   http://localhost:5173/
➜  Network: use --host to expose
➜  press h + enter to show help
```

### Ways to Start Application

1. `npx vite`
2. `npm run dev`

### Ways to Build Application

1. `npx vite build`
2. `npm run build`

### Running in Development Mode

```bash
npm run dev
```

### Running in Production Mode

First, build the application:
```bash
npm run build
```

Then, preview the production build:
```bash
npm run preview
```

## Plugins

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
"# myfirstvitereactapp2025" 

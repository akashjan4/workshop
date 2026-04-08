<details>
  <summary>Setup: Introduction</summary>

  - Latest Version: [19.2](https://react.dev/versions#latest-version)
  - Version used: 
    - [18.x](https://2025.stateofreact.com/en-US/usage/)
    - [Documentation](https://18.react.dev/)
    - Release Date: March 29, 2022
    - Last Released version: v18.3.1 (April, 2024) [changelog](https://github.com/facebook/react/blob/main/CHANGELOG.md#1831-april-26-2024)
    - Key Features
      -  **Automatic Batching** 
          -  Fewer re-renders for better performance 
          -  Works outside of event library 
          -  Safe, but you can opt out when needed
      -  **Suspense on the server** 
          -  Server side rendering is a technique where html of your react page is sent from your server to client so that it can render UI. The JS of App is still be loading and you webpage will not interactive till it's not fully loaded.
          -   The react page could have many components and few them can take still take time to load because of any heavy operation.
          -   The slow part/component of your page can be wrapped around `<Suspense>`, telling react to delay loading of this component. It also support loading state, so we can show a spinner if we need to. 
          -   One Slow part of page doesn't slowdown the whole page
          -   Show initial HTML early and stream the rest 
          -   Code splitting fully integrated with server rendering. 
      -  **New APIs for app and library developers**
          -  `startTransition()`
          -  `useTransition()`
          -  `useDeferredValue()`
          -  `useId()`
          -  `useSyncExternalStore()`
</details>

<details>
  <summary>Why not latest React 19?</summary>

---
| Factor                        | React 18  | React 19             |
| ----------------------------- | --------- | -------------------- |
| Learning curve                | Easy      | Medium–High          |
| Works with simple Vite setup  | ✅         | ⚠️ sometimes tricky  |
| AI-generated code reliability | ✅ high    | ⚠️ mixed             |
| Ecosystem tutorials           | ✅ massive | ⚠️ still catching up |

### Other factors 
- Most companies are still using React 18
- Fundamental skills (hooks like useState, useEffect, etc.) matter more than version-specific features. React 19 doesn’t drastically change how React works at its core.
- React 19 is too new. React 19 ecosystem is still catching up
- React 18 has:
  - More tutorials
  - More community support
  - More stable tooling

</details>

<details>
  <summary>Pre-requisite</summary>

  - [Node Version Manager](https://www.nvmnode.com/) or [Fast Node Version Manager](https://github.com/Schniz/fnm) 
  - NodeJS version 22
  - Package manager [npm](https://www.npmjs.com/)/[yarn](https://yarnpkg.com/)/pnpm/bun/deno
  - [Build Tool - Vite](https://vite.dev/guide/)

</details>

<details>
  <summary>React Installation Steps</summary>
    
  - Install the latest react version using vite 
    - `npm create vite@latest <application-name> -- --template react`
  - `cd <application-name>`
  - Downgrade the react and react dom libraries 
    - `npm install react@18 react-dom@18`
</details>

<details>
  <summary>Common commands</summary>

  - Run: `npm run dev`
  - Build: `npm run build`
  - Lint check: `npm run lint`
  - Build preview: `npm run preview`
    
  **NOTE**: Check [package.json](./package.json)
</details>

<details>
<summary>React + Vite</summary>

## Disclaimer
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

</details> 

<details Open>
  <summary>Post Setup: Plan</summary>

## Introduction to React
  - What is React & why it’s used
  - SPA concept
  - Virtual DOM (very high level, no deep theory)
  - Setup using Vite

## Project Setup
  - Create Vite app
  - Folder structure
  - Run dev server

## JSX & Components
  - JSX basics
  - Functional components
  - Props
  - **Hands-on**:
    - TODO: Akash to decide
  
## State & Events
  - `useState` (basic understanding)
  - Event handling (`onClick`, `onChange`)
  - **Hands-on**:
    - TODO: Akash to decide

## Hooks
  - `useState` (deep understanding)
  - `useEffect`
  -  **Hands-on**:
     - TODO: Akash to decide

## API Calls (Mock / Public API)
- fetch() or Axios
- useEffect for API calls
- Loading & error state (basic)
- **Hands-on**:
  - TODO: Akash to decide

</details>
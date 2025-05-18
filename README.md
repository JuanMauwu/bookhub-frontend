# React + Vite

##Technologies used

- Node.js
- React
- Vite 
- npm


##Create project

- Go to [https://nodejs.org/](https://nodejs.org/) and download the **LTS version (recommended)**. This will automatically install **Node.js** and **npm**.

- Verify the versions of Node.js and npm (Node Package Manager): 
    - `node -v`
    - `npm -v`

- Create project:
    - `npm create vite@latest`

- Install the dependencies:
    - `npm install`

- Start project:
    - `npm run dev`

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
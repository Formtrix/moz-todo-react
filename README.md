# React + Vite

Learning React and JavaScript core

In this project:

React was powered by Vite with HMR and some ESLint rules.

Currently, two official plugins were used:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

App UI sneak peek!

- [UI ](./doc/images/todo.pdf)
- [Screen](./doc/images/todo0.pdf)

##### Want to run the app? Let's go

#### Run the app

_Before setting up and running the app, I recommend getting conformtable with JSX syntax for react apps._

Typical JSX Syntax
`const heading = <h1>Keny Kit Developer Network</h1>;`

What we will need and what you should know.

- Vite: this project was generated from Vite's standard React template, **Create React App** command has been deprecated by React team.
  [Vite](https://vite.dev/) is a modern front-end build tool.
- Node: before we can use Vite, we need to have **Node** installed.
  As of Vite 5.0, at least [Node](https://nodejs.org/en/download) version 18 or later is needed, and latest Node (LTS) is fine.
  Install and check [Node](https://nodejs.org/en/download) version

  ```zsh
  node -v
  ```

  It should return a version number for confirmation of successful install, this also installs **NPM**.

  After successful Node installation, we can use the Node Package Manager(NPM) to create fresh project from Vite's React Template.
  [NPM](https://www.npmjs.com/) has create command that we can use to create new projects from templates.
  In a terminal `cd` to local directory where the app will live locally, then run

  ```zsh
  npm create vite@latest  -- --template react
  ```

  This will create new React App with Vite's support; however, **we are not creating new app**, we just want to run the one in this repo.
  So, clone this repo with `git clone https://github.com/user/repo.git`, for example

  ```zsh
  git clone https://github.com/octocat/Hello-World.git
  ```

  Down to a local directory and `cd` to the root of the app and run

  ```zsh
  npm run dev -- --open --port 3000
  ```

  If you wrong into error, check

  - Node Version
  - If on Windows, may need WSL

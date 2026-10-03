# registrarMenuReacts

A small React + Reflux practice app implementing a "Register Menu" form (`Registrar Menú`) — a simple form to register a menu item with name, price, and description, using the Flux/Reflux unidirectional data flow pattern.

## Tech stack

- React 15
- Reflux (Flux-like actions/stores)
- jQuery, Bootstrap (via CDN, for styling)
- Webpack + webpack-dev-server for bundling/dev server

## Project structure

- `index.html` – app shell (loads Bootstrap/jQuery from CDN and mounts the app)
- `src/components/Form.jsx` – the menu registration form component
- `src/actions/MenuAction.js` – Reflux actions
- `src/stores/MenuStore.js` – Reflux store holding form state

## Running it

```bash
npm install
npm start
```

This runs `webpack-dev-server --hot` for local development.

## Context

This is a personal practice project for learning the React + Flux/Reflux architecture. Note: there is a near-identical sibling repository, `registrarmenu`, containing the same exercise/source code.

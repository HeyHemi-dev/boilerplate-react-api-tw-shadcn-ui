# DevAcademy Boilerplate with Shadcn UI:

## About DevAcademy Boilerplate: React with Express, Vite

This is a starter project that uses Vite to bundle a React app and Express to serve it in production. Express is used in development to serve an API server.

Vite React App: [http://localhost:5173](http://localhost:5173)
Express API Server: [http://localhost:3000](http://localhost:3000)

Requests to `http://localhost:5173/api` are proxied to `http://localhost:3000/api`.

## About Shadcn UI

> Shadcn UI is a set of [beautifully designed components](https://ui.shadcn.com/) that you can copy and paste into your apps. 
> Accessible. Customizable. Open Source.

Shadcn is not a UI component library, instead it allows you build your own component library. Each ui element is ready to go with sensible defaults, but because you own the code, you can tailor each component specifically for your app.

### How to Add UI Components

Browse the [UI components](https://ui.shadcn.com/docs/components/). To use each UI component there are typically three steps:

1. Run the CLI install command (installs into `components/ui`).
2. Copy/paste the import into your react component.
3. Copy/paste ui elements into your react component.

## Setup

### Installation

To use, consider these steps:

- Fork this repo
- Rename your repo according to the app you're building

```sh
git clone https://github.com/[your-account]/[your-app].git
cd [your-app] && npm i
```

To start the development server with a watcher that rebuilds your code, run `npm run dev`.

Additional components should be placed in `client/components`.

### Pre-Installed modules

- Vite
- Vitest
- Express
- Tanstack Query (aka React Query)
- Prettier
- Supertest
- Tailwind
- Shadcn UI
- Superagent
- Knex
- SQLite3

### Recommended modules

| Purpose          | Module           | Installation |
|------------------|------------------|--------------|
| Front end router | React Router Dom | `npm install react-router-dom` |

# vue-3-pinia-jwt-refresh-tokens

Vue 3 + Pinia - Authentication by JWT with Refresh Tokens Example and Tutorial

Last updated: 26-01-2026

Node version: 24.13.0

Volta commands used:

Fetch and use a particular version of Node globally at your computer:

volta install node@24

Volta lets you choose your Node engine and package manager for a project once with one command:

volta pin node@24

List the node at your computer:

volta list node

# Tech used for this Web Client

- Node.js version 24.13.0
- Volta for Node Version management
- Vue 3 is the JS framework for this frontend
- Pinia for state management
- ESLint for analysing the .JS code
- Vee-validate for validation
- Yup for validation
- vite v2.9.16 Dev Server
- VS Code is my developement tool
- Hosted ata traditional Webhotel

# Installing

- Make sure you have a new version of Node installed
- Download the code by zip or fork
- Run the command npm install by the command promt

# Development server:

- npm run dev

- You can view the development server at `localhost:3000`

# Production build:

- npm run build

# Preview before Publish / Deployment

- npm run preview

- You can view the preview production built at `localhost:5050`

# Tech used for the Web API for this Web Client

- Python FastAPI
- PostgreSQ
- OpenAPI / Swagger
- Serves Auth by JWT with Refresh Tokens
- Hosted at Vercel Cloud using Serverless Functions

# Things to consider for future versions

- Set the minuttes for the JWT Access Tokens to 15 in .env

- Set the minuttes for the JWT Refresh Tokens to 7 DAYS in .env

- Implement Refresh token rotation

- Implement Revoked token reuse detection

- Protect the API Routes by Rate limits

The Vue + FastAPI was made in a simple way for showing the Authentication flow by JWT and Refresh Tokens

Happy coding :-)

See Demo : https://scholarshipportalnew.netlify.app/
<img width="478" height="808" alt="image" src="https://github.com/user-attachments/assets/a908f141-95b1-45b7-bbc7-fdafde85e88e" />
# Scholarship Portal Frontend

A frontend application for the Scholarship Portal project. This repository contains the client-side code that implements the user interface for applicants, administrators, and reviewers to interact with the scholarship system.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the app (development)](#running-the-app-development)
  - [Building for production](#building-for-production)
  - [Environment variables](#environment-variables)
- [Folder structure](#folder-structure)
- [Testing](#testing)
- [Linting & Formatting](#linting--formatting)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

This project provides the frontend for a Scholarship Portal where students can apply for scholarships, upload required documents, track application status, and administrators can create and manage scholarship listings, review applications, and communicate with applicants.

## Features

- User authentication (applicants, reviewers, admins)
- Scholarship listing and detail pages
- Application submission with file uploads
- Dashboard pages for applicants and administrators
- Application review workflow and status updates
- Responsive UI for desktop and mobile

> Note: The backend API endpoints, auth flows, and environment variable names should match the backend implementation. See the `Environment variables` section below.

## Tech stack

- JavaScript (or TypeScript) and a modern front-end framework (React, Vue, or similar)
- CSS / SCSS or UI library (Tailwind / Bootstrap / Material UI — adjust per repo)
- Build tooling: npm / yarn, bundler (Vite, Webpack, or framework CLI)
- Testing: Jest / React Testing Library (if present)

Modify this section to match the actual stack (React / Vue / Next.js / etc.) used in this repository.

## Getting Started

### Prerequisites

- Node.js (LTS recommended: 16 or newer)
- npm (>= 8) or yarn

### Installation

1. Clone the repository
   ```
   git clone https://github.com/Sumit1911/scholarshipPortalFrontend.git
   cd scholarshipPortalFrontend
   ```

2. Install dependencies
   ```
   npm install
   # or
   yarn install
   ```

### Running the app (development)

Start the development server (adjust script name if your package.json uses a different script, e.g., `dev`, `start`, or `serve`):

```
npm run dev
# or
npm start
# or
yarn dev
```

Open http://localhost:3000 (or the port printed in the terminal) to view the app.

### Building for production

Build production assets:

```
npm run build
# or
yarn build
```

Serve the `dist`/`build` folder with a static server or deploy to your hosting provider.

### Environment variables

Create a `.env` file in the project root (or copy `.env.example` to `.env`) and add variables required by the app, for example:

```
VITE_API_BASE_URL=https://api.example.com
REACT_APP_API_BASE_URL=https://api.example.com
# OAUTH_CLIENT_ID=...
# OTHER_KEY=...
```

Adjust variable names to match the codebase.

## Folder structure

A typical frontend structure (update to match this repository):

```
/src
  /components     # UI components
  /pages          # Route pages or views
  /services       # API calls
  /hooks          # Custom hooks
  /assets         # Images, fonts
  /styles         # Global styles
  main.js / index.js
/public or /static
package.json
```

## Testing

If tests exist, run them with:

```
npm test
# or
yarn test
```

Add unit and integration tests focused on critical components (forms, routing, API interactions).

## Linting & Formatting

If ESLint/Prettier are configured:

```
npm run lint
npm run format
# or
yarn lint
yarn format
```

Follow the repository's code style and lint rules when contributing.

## Deployment

Common deployment targets:

- Vercel (recommended for Next.js or Vite projects)
- Netlify
- GitHub Pages (for static builds)
- Docker container + cloud provider (AWS/GCP/Azure)

Set environment variables in the hosting provider dashboard and point the build command to `npm run build`.

## Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch: `git checkout -b feat/your-feature`
3. Commit your changes: `git commit -m "feat: add ..."`
4. Push: `git push origin feat/your-feature`
5. Open a Pull Request describing your change

Please open issues for bugs and feature requests. Include screenshots, steps to reproduce, and relevant logs.

## License

This project is available under the MIT License. Update the license section if another license applies.

## Contact

Repository owner: [Yash Modi] (https://github.com/YashModi1804)

For questions or help, open an issue on the repository.

# Coffee Shop

## Overview

Coffee Shop is a web application project focused on creating an online storefront where users can explore coffee products. The goal is to build a clean, user-friendly shopping experience while practicing modern web development.

## Technologies Used

**Frontend**
- Next.js
- React
- TypeScript
- Tailwind CSS

**Backend**
- Node.js
- Express.js

## Project Structure

- `client/` — Contains the frontend application.
- `server/` — Contains the backend application and API.

## Getting Started

### Prerequisites

- Node.js and npm installed.

### Frontend

Navigate to the `client` directory, install the dependencies, and start the development server using the scripts defined in `client/package.json`.

### Backend

Navigate to the `server` directory, install the dependencies, and start the server using the scripts defined in `server/package.json`.

## Current Status

The initial project structure and development environments have been established. Frontend features, product listings, shopping cart functionality, and backend integrations are planned for future development.

## Git Workflow

This project uses a branch-based workflow to keep development organized and maintain a stable main branch.

### Branches

- `main` — Contains stable code that is ready for release.
- `dev` — Integrates completed features and bug fixes for testing before release.
- Feature branches — Used to develop individual features, documentation updates, and bug fixes without directly modifying `main` or `dev`.

### Branch Naming

Branches should have descriptive names that identify the work being performed.

Examples:
- `feature/product-card`
- `feature/shopping-cart`
- `fix/cart-total`
- `docs/readme-update`

### Pull Requests

1. Create a task branch from `dev` for each issue.
2. Make changes on the task branch and commit them with descriptive commit messages.
3. Open a pull request from the task branch into `dev`.
4. Review the changes and verify that the acceptance criteria are satisfied before merging.
5. Test the integrated changes in `dev`.
6. When `dev` is stable and ready for release, open a pull request from `dev` into `main`.

### Testing and Code Quality

Changes should be tested before they are considered complete. Pull requests should be reviewed for correctness, readability, and consistency with the project's requirements. Any identified issues should be addressed before merging.

### General Guidelines

- Avoid committing directly to `main`.
- Use a separate task branch for each issue whenever practical.
- Keep pull requests focused on a single task or closely related changes.
- Never commit API keys, passwords, or other sensitive information.
- Update project documentation when changes affect setup instructions, architecture, or development practices.

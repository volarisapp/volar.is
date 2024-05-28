# Volaris Website

This repository contains the source code for the Volaris website, a project built using Svelte and Tailwind CSS to provide a modern, responsive, and interactive user interface.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The project is structured as follows:

```
volar.is/
├── public/ # Static assets
├── src/
│ ├── lib/ # Library code (e.g., global CSS)
│ ├── routes/ # Svelte routes
│ │ ├── about/ # About page
│ │ ├── download/ # Download page and subpages
│ │ ├── contact/ # Contact Page
│ │ └── +page.svelte # Home page
│ └── app.html # HTML template
├── static/ # Static files served as-is
├── package.json # Project dependencies and scripts
└── svelte.config.js # Svelte configuration
```
and so on.


## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

    `git clone https://github.com/volarisapp/volar.is.git`

2. **Navigate to the project directory:**

    `cd volar.is`

3. **Install dependencies:**

    `npm install` or `pnpm install`

## Running the Project

To run the project locally, use the following command:

`npm run dev` or `pnpm run dev`

This will start a local development server. Open your browser and navigate to `http://localhost:5173` to see the website.

## Deployment

To build the project for production, use the following command:

`npm run build` or `pnpm run build`

This will create an optimized build of the project in the `public` directory. You can then deploy the contents of this directory to your web server or a static site hosting service.

## Contributing

We welcome contributions! If you'd like to contribute, please fork the repository, create a new branch, and submit a pull request. Please make sure to follow the project's coding standards and include appropriate tests.

**Note:** This repository uses conventional commits. Please follow the [conventional commits guidelines](https://www.conventionalcommits.org/en/v1.0.0/) for your commit messages.

## License

This project is licensed under the BSD 2-Clause License. See the `LICENSE` file for more details.

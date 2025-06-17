# Tailwind CSS Project

This project demonstrates the implementation and usage of Tailwind CSS for modern web development. It includes examples of traditional CSS styling alongside Tailwind's utility-first approach.

## Project Overview

This project contains two HTML implementations:
- `index.html`: A traditional approach with inline CSS
- `tailwind.html`: The same design implemented with Tailwind CSS classes

## Project Structure

```
.
├── build/                 # Build output directory
├── src/
│   ├── index.html         # Traditional CSS implementation
│   ├── tailwind.html      # Tailwind CSS implementation
│   └── styles/
│       ├── input.css      # Tailwind directives
│       └── styles.css     # Generated CSS output
├── package.json           # Project dependencies and scripts
├── postcss.config.js      # PostCSS configuration
├── README.md              # Project documentation
└── tailwind.config.js     # Tailwind configuration
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or newer)
- npm (comes with Node.js)

### Installation

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

## Available Scripts

In the project directory, you can run:

### `npm run build`

Processes the Tailwind directives in `src/styles/input.css` and generates the complete CSS in `src/styles/styles.css`.

### `npm run build:watch`

Same as `build`, but watches for file changes and rebuilds automatically.

### `npm run dev:css`

Builds the CSS and launches a live server with the traditional CSS implementation (`index.html`).

### `npm run dev:tw`

Builds the CSS and launches a live server with the Tailwind implementation (`tailwind.html`).

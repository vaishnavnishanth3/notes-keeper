# Notes Keeper

A simple notes app built with React and Vite.

## Features

- Add notes with a title and content
- Display all created notes
- Delete notes individually
- Clean, minimal Keeper-style UI

## Tech Stack

- React 17
- Vite 5
- ESLint

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Installation

```bash
npm install
```

### Run in Development

```bash
npm run dev
```

Then open the local URL shown in the terminal (typically `http://localhost:5173`).

## Available Scripts

- `npm run dev` – Start Vite dev server
- `npm run build` – Create production build
- `npm run preview` – Preview production build locally
- `npm run lint` – Run ESLint checks

## Project Structure

```text
src/
  index.jsx
  components/
    App.jsx
    Header.jsx
    Footer.jsx
    CreateArea.jsx
    Note.jsx
public/
  styles.css
```

## Current Behavior & Limitations

- Notes are stored only in component state (`useState`)
- Notes are not persisted after page refresh
- There is no backend or database integration

## License

This project is private and intended for learning/development use.

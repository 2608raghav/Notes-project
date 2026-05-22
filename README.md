# Notes App

A simple React note-taking application built with Vite and Tailwind CSS.

## Overview

This project allows users to add and delete notes using a minimal form-based interface.

Features:
- Add a note title and details
- Display notes as cards
- Remove notes individually
- Built with React 19, Vite, and Tailwind CSS

## Project Structure

- `src/App.jsx` — main app logic and note state
- `src/main.jsx` — React app entry point
- `src/index.css` — global styles
- `package.json` — dependencies and scripts

## Installation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open the local URL shown in the terminal.

## Usage

- Enter a note title in the first input field.
- Enter note details in the textarea.
- Click `Add Note` to save the note.
- Notes appear on the right and can be deleted using the `Delete` button.

## Scripts

- `npm run dev` — start Vite development server
- `npm run build` — build production bundle
- `npm run preview` — preview production build locally
- `npm run lint` — run ESLint checks

## Dependencies

- `react`
- `react-dom`
- `tailwindcss`
- `@vitejs/plugin-react`
- `vite`

## Notes

This app stores notes in React component state only. Refreshing the page will clear all notes.

For persistence, you can extend the app with `localStorage` or backend storage.

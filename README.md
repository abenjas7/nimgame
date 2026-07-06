# Nim Game Frontend

React frontend for a web implementation of the Nim game.

The application provides an interactive board where the user selects adjacent sticks from one row, confirms moves, and can ask the computer to play. It communicates with the Flask backend hosted in the companion repository [`api_nim`](https://github.com/abenjas69/api_nim).

## Main Features

- Interactive Nim board with row and stick selection.
- Client-side validation for row consistency and adjacent stick selection.
- REST communication with the backend through Axios.
- Per-user game sessions using a browser-generated `X-User-ID` header.
- Game controls for new game, player move, computer move, and rules display.

## Stack

- React 18
- Axios
- Tailwind CSS
- Create React App

## Backend

The frontend currently points to:

```text
https://api-nim.onrender.com
```

The backend repository is available at:

```text
https://github.com/abenjas69/api_nim
```

## Local Setup

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm start
```

Build for production:

```bash
npm run build
```

## Portfolio Note

This project demonstrates frontend development, REST API integration, state management, user interaction rules, and deployment-oriented separation between frontend and backend.

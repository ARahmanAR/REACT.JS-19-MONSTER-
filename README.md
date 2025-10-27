# REACT.JS 19 MONSTER

A modern Monster Rolodex application built with **React 19** and **Vite**. This project demonstrates React 19 features including hooks, component composition, and state management.

## Features

- 🎨 Modern UI with gradient backgrounds and hover effects
- 🔍 Real-time search filtering
- 👾 Monster cards with Robohash avatars
- ⚡ Built with Vite for lightning-fast development
- 📦 React 19.1.1

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint
```

## Project Structure

```
src/
├── components/
│   ├── Card.jsx          # Individual monster card component
│   ├── Card.css
│   ├── CardList.jsx      # Grid of monster cards
│   ├── CardList.css
│   ├── SearchBox.jsx     # Search input component
│   └── SearchBox.css
├── App.jsx               # Main application component
├── App.css
├── main.jsx             # Application entry point
└── index.css            # Global styles
```

## Technologies Used

- **React 19.1.1** - Latest React with improved hooks and performance
- **Vite 7.1.7** - Next generation frontend tooling
- **ESLint** - Code linting and quality
- **Robohash API** - Dynamic monster avatars
- **JSONPlaceholder** - Mock user data

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Learn More

- [React Documentation](https://react.dev)
- [Vite Documentation](https://vite.dev)

## License

This project is licensed under the MIT License - see the LICENSE file for details.


# Streaks

Habit tracker front end built with React 18 + Vite. Data is stored in the browser (localStorage).

    npm install
    npm run dev       # development server
    npm run build     # production build in dist/

Requires Node.js 18+.

Structure: `src/utils.js` (date and streak helpers), `src/useHabits.js` (state + persistence),
`src/components/` (Dashboard, Habits, Stats), `src/App.jsx` (layout, navigation, theme).

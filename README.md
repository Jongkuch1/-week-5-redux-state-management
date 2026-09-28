# Week 5 Guided Activity — Redux State Management

A React + TypeScript app demonstrating manual Redux state management (without Redux Toolkit): a counter with increment, decrement, and reset actions, wired up with `redux`, `react-redux`, and `redux-logger`.

## Tech Stack

- Vite
- React
- TypeScript
- Redux (manual setup, no Redux Toolkit)
- React-Redux
- Redux-Logger

## Getting Started

```bash
npm install
npm run dev
```

The app runs at `http://localhost:5173/`.

## Project Structure

```text
src/
  components/
    Counter.tsx
    Counter.module.css
  store/
    store.ts
    actions/
      counterActions.ts
    reducers/
      counterReducer.ts
      index.ts
```

## Features

- Redux store configured with `redux-logger` middleware
- Counter actions: `INCREMENT`, `DECREMENT`, `RESET`
- Global state read via `useSelector`
- State updates dispatched via `useDispatch`

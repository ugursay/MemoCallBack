# React App with useCallback Hook

This is a simple React application that demonstrates the use of the `useCallback` hook to optimize performance in a functional component.

## Features

- **Dynamic List**: The app takes an input value and dynamically generates a list of numbers based on that value.
- **Dark/Light Theme**: You can toggle between dark and light themes with a button.

## How It Works

- **State Management**: The app uses `useState` to manage the current number and theme state.
- **Callback Optimization**: The `useCallback` hook is used to optimize the `getItems` function, which generates an array of numbers based on the input value. This prevents unnecessary re-creations of the `getItems` function on each render.
- **useEffect**: The `useEffect` hook in the `NumberList` component is used to update the list when the input value changes.

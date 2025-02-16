# Infinite Rendering Loop in React Component

This repository demonstrates a common error in React applications: an infinite rendering loop caused by the incorrect use of the `useEffect` hook.

## Bug Description
The `bug.js` file contains a React component that uses the `useEffect` hook without specifying a dependency array. This causes the effect to run after every render, leading to an infinite loop.

## Bug Solution
The `bugSolution.js` file demonstrates the corrected version of the component. The dependency array is now correctly specified, ensuring that the effect only runs when the necessary state values change.
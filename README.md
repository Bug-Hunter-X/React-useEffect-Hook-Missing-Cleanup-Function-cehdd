# React useEffect Hook Missing Cleanup Function

This repository demonstrates a common error in React applications: forgetting to include a cleanup function in the `useEffect` hook. This can lead to memory leaks and unexpected behavior.

## The Bug
The `bug.js` file contains a component that uses the `useEffect` hook to log a message to the console when the component mounts. However, it's missing a return statement which would handle the cleanup.
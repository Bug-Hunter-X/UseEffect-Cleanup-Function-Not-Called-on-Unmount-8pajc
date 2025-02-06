# useEffect Cleanup Function Not Called on Unmount
This example demonstrates a common issue with React's useEffect hook where the cleanup function is not called when the component unmounts.  This can lead to memory leaks or unexpected behavior.

## Problem
The provided `MyComponent` uses `useEffect` without a condition.  Even when the component is unmounted, the cleanup function won't run properly.
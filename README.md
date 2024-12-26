# React Native Unhandled JS Exception: Cannot read properties of undefined (reading 'name')

This repository demonstrates a common React Native error and its solution. The error, "Unhandled JS Exception: Cannot read properties of undefined (reading 'name')", arises when attempting to access a property of an object that is null or undefined. This often happens when dealing with asynchronous operations or data fetching where data might not yet be available.

The example code shows how this error can occur when accessing the `name` property of a `user` object before the data is fetched and assigned.

The solution demonstrates how to handle this using optional chaining (`?.`) and nullish coalescing (`??`) operators for safe access to properties and providing default values.

## How to reproduce the bug
1. Clone the repository.
2. Run `npm install`.
3. Run `npx react-native run-android` or `npx react-native run-ios`.
4. Observe the error in the console.

## How to solve the bug
Refer to `bugSolution.js` for the solution using optional chaining and nullish coalescing.
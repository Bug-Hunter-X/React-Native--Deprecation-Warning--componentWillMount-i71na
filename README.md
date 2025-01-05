# React Native: Deprecation Warning: componentWillMount

This repository demonstrates a common error in React Native: the use of the deprecated `componentWillMount` lifecycle method.  This method is no longer recommended and may lead to unexpected behavior or crashes.  This example shows the problem and how to fix it using the recommended `useEffect` hook.

## Bug

The `bug.js` file contains code that utilizes `componentWillMount`.  This will trigger a deprecation warning in the console. 

## Solution

The `bugSolution.js` file shows the correct way to replace `componentWillMount` with `useEffect`.  This ensures compatibility with newer versions of React Native and avoids the warning.

## How to run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npx react-native run-android` or `npx react-native run-ios`. (Depending on your setup)
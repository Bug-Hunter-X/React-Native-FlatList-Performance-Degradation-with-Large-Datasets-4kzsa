# React Native FlatList Performance Issue

This repository demonstrates a common performance problem encountered when using the `FlatList` component in React Native with large datasets.  The issue is slow scrolling and potential crashes due to inefficient rendering.  The solution involves optimizing the `renderItem` function and utilizing key extractors.

## Bug

The `FlatListBug.js` file showcases the problematic implementation.  It renders a large number of items without proper optimization, leading to performance issues.

## Solution

The `FlatListBugSolution.js` file provides an optimized solution.  It implements key extractors and improves the `renderItem` function to enhance performance.  The changes significantly improve scrolling speed and prevent crashes.

## How to reproduce the bug

1. Clone this repository.
2. Run `npm install`.
3. Run the app using your preferred React Native method.  Observe the slow scrolling.

## How to test the solution

1. Switch to the `FlatListBugSolution.js` file.
2. Re-run the app.  Notice the significant improvement in scrolling performance.
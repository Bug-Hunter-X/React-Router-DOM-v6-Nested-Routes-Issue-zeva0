# React Router DOM v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router DOM v6.  The problem manifests as unexpected behavior, particularly concerning rendering and route matching when using dynamic segments or complex route structures. 

The `bug.js` file contains the problematic code, showcasing the incorrect rendering.  The `bugSolution.js` offers a corrected implementation.  This example utilizes a simple structure for clarity, although the issue can appear in more complex scenarios.

## How to reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Observe the unexpected routing behavior.

## Solution

The solution involves carefully structuring routes and potentially using route parameters more effectively.  See `bugSolution.js` for a corrected implementation and a more in-depth explanation of the solution.

## Additional context

Ensure you are using the latest version of React Router DOM.  Review the official documentation for best practices regarding nested routes and route parameters.
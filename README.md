# Expo Image Component: 404 Error Handling

This repository demonstrates a bug in the Expo Image component where it does not handle 404 errors gracefully from remote image URLs.  The component may crash or fail to render, providing unhelpful error messages.

## Bug Reproduction

The `bug.js` file shows how to reproduce the bug.  It attempts to load an image from a URL known to return a 404.  Observe the behavior of the app.

## Solution

The `bugSolution.js` file provides a solution to this problem. It implements error handling to gracefully manage the situation where the image fails to load, improving the user experience.

## Contributing

Contributions are welcome!
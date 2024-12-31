# Firebase Realtime Database: ServerValue.TIMESTAMP Error

This repository demonstrates a common, yet subtle, error when using Firebase's `ServerValue.TIMESTAMP` in the Realtime Database. The error, `Error: Database.ServerValue.TIMESTAMP is not a function`, arises from incorrect usage of `ServerValue.TIMESTAMP`.

The `bug.js` file shows the problematic code.  The `bugSolution.js` file provides the correct implementation.

## Setup

1.  Ensure you have Node.js and npm (or yarn) installed.
2.  Install Firebase:
    ```bash
npm install firebase
```
3.  Configure your Firebase project.  Replace placeholders in `bug.js` and `bugSolution.js` with your Firebase config.

## Usage

Run `bug.js` to see the error. Run `bugSolution.js` to see the correct implementation and successful database update.
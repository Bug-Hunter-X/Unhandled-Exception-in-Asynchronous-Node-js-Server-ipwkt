# Unhandled Exception in Asynchronous Node.js Server

This repository demonstrates a common error in Node.js where an unhandled exception within an asynchronous operation causes the server to crash.  The provided `bug.js` file showcases the problematic code. The solution, in `bugSolution.js`, addresses this by properly handling the exception using error handling mechanisms.

## Bug
The `bug.js` file contains a simple HTTP server that simulates an asynchronous operation that might fail. If the operation fails, it throws an error without proper error handling, causing the server to crash.

## Solution
The `bugSolution.js` file demonstrates the correct way to handle exceptions within asynchronous operations in Node.js. It uses a `try...catch` block to gracefully handle errors, preventing the server from crashing.
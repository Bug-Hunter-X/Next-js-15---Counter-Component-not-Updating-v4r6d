# Next.js 15 - Counter Component Not Updating

This repository demonstrates a bug in a Next.js 15 application where a simple counter component fails to update its state after a button click.  The issue stems from the way state is managed within the functional component. 

## How to reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install the dependencies.
4. Run `npm run dev` to start the development server.
5. Observe that clicking the button does not increment the counter.

## Solution

The solution involves ensuring the component re-renders after updating the state. The provided solution demonstrates the correct usage of useState and how to trigger a re-render to solve the problem.
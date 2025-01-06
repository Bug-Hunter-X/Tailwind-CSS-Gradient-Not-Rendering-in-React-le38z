# Tailwind CSS Gradient Bug in React

This repository demonstrates a bug where a Tailwind CSS gradient doesn't render correctly in a React component. The gradient appears as a solid color instead of the expected smooth transition between colors.

## Bug Description

The `MyComponent` component uses Tailwind CSS classes to create a background gradient. However, instead of a gradient, a solid color is rendered. 

## Solution

The bug was caused by incorrect usage of the gradient direction property of Tailwind CSS, solved by specifying the direction correctly.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the rendered component in the browser. The gradient will appear as a solid color instead of a gradient.

## Troubleshooting

Check your Tailwind configuration file (`tailwind.config.js`) to ensure that the gradient functionality is properly configured and that the correct plugins are enabled. 

If you still encounter issues, feel free to open an issue in this repository. 

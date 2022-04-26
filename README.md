TypeScript Boilerplate
======================

This is boilerplate project is the basis of many of my TypeScript projects. Feel free to use it for yourself!

Includes:
* Simple set of TypeScript setup
* automatic code linting on each commit using eslint via husky and lint-staged
* automatic code prettifying on each commit using prettier via husky and lint-staged
* My preferred set of linting rules for a consistent style

## How to use
- `npm run build` to once compile the TypeScript files into JavaScript files into the `/dist` directory
- `npm run watch` continuously recompile on any change
- You can run the example output using `node dist/` which will pick up the compiled JavaScript

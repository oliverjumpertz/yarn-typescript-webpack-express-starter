# Yarn TypeScript Webpack Express Starter
## What is this?
This is a template for development of an Express API with TypeScript and bundling through webpack.
Code is written in JS/TS and tested with mocha and chai. For deployments, a single `bundle.js` is created with webpack.
The `package.json` does already contain some useful scripts.

`$ yarn dev` will quickly compile your sources during development and start the server.

`$ yarn test` will run all the tests you've written with mocha and chai.

`$ yarn build` will trigger the whole build process and use webpack to create a bundle which you can simply deploy (to a Docker container, e.g.).

`$ yarn start` will use build and start your API from the created `bundle.js`.

## Dependencies
- TypeScript
- TSLint
- Yarn
- Mocha (including types)
- Chai (including types)
- Express
- webpack

## Usage
Fork or clone if you like. Feel free to delete `.git` afterwards and use this as the base for your own project.

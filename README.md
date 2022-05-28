# React - boilerplate :- - https://theroadtoenterprise.com/

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and enhanced with additional config and tools.

## Project Configuration

- Setup directory structure
- Configured absolute path resolving. `@` is configured to point at the `src` directory. You can import files like this: `import styles from "@/styles/Home.module.css"`
- Configured Stylelint and Prettier
- Extended eslint rules to avoid collisions with Prettier
- Added new lint and fix scripts
- Configured [husky](https://typicode.github.io/husky/#/) and [lint-staged](https://github.com/okonet/lint-staged) to lint staged files on commit
- Added `src/api` logic
- Added various PostCSS plugins - see `postcss.config.js` file.
- Configured Cypress with Testing Library
- Configured Jest with Testing Library

## Installed Libraries

### E2E Testing

- cypress
- @testing-library/cypress
- start-server-and-test

### Unit Testing

- jest
- @testing-library/react
- @testing-library/user-event
- @testing-library/react-hooks - Testing hooks
- msw - Mocking APIs

### API

- axios

### Linting and code formatting

- eslint
  - eslint-config-next
  - eslint-config-prettier
- stylelint
  - stylelint-config-css-modules
  - stylelint-config-prettier
  - stylelint-config-recess-order
  - stylelint-config-recommended
  - stylelint-config-standard
  - stylelint-scss
- prettier
- lint-staged
- husky

### PostCSS

- postcss-extend
- postcss-flexbugs-fixes
- postcss-import
- postcss-preset-env
- postcss-reporter
- precss

### Utilities

- clsx
- lodash-es

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

## Useful links

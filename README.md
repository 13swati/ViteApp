 3Getting Started with Create React App

This project was made to test my react code
[Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

When you run the `npm start` command in a Node.js project, it typically does the following:

1. **Starts the Development Server:** Launches a local server to serve the application during development.
2. **Opens the Application in a Browser:** Automatically opens the application in the default web browser.
3. **Enables Live Reloading:** Watches for changes in the source files and automatically reloads the application when changes are detected.

In the context of a Create React App project, `npm start` runs the app in development mode at [http://localhost:3000](http://localhost:3000).

For more details, you can refer to the [official Create React App documentation](https://create-react-app.dev/docs/getting-started).

### `npm test`
When you run the `npm test` command in a Node.js project, it typically performs the following:

1. **Runs Test Suites:** Executes the test scripts defined in your project. For a Create React App project, it uses Jest as the test runner.
2. **Displays Results:** Shows the results of the test cases, indicating which tests passed and which failed.
3. **Watches for Changes:** In watch mode, it reruns tests automatically when changes are made to the source files or test files.

In the context of Create React App, `npm test` runs the app’s test suite in interactive watch mode.

### `npm run build`
Running `npm run build` in a Create React App project generates a production-ready build of your application. Here's what it does:

1. **Transpiles JavaScript:** Converts modern JavaScript into a version compatible with older browsers.
2. **Minifies Code:** Reduces the size of JavaScript, CSS, and HTML files to improve load times.
3. **Optimizes Assets:** Compresses images and other static assets.
4. **Bundles Files:** Combines JavaScript modules into a single file to reduce HTTP requests.
5. **Generates Source Maps:** Helps in debugging minified code.
6. **Creates Build Directory:** Places all optimized files in a `build` folder.

You can then deploy the contents of the `build` folder to a web server.

### `npm run eject`

Running `npm run eject` in a Create React App project permanently exposes the configuration files and dependencies used by Create React App. This includes Webpack, Babel, ESLint configurations, and more.

Here's what happens when you eject:

1. **Copies Configuration Files:** Moves configuration files into your project, giving you full control.
2. **Modifies package.json:** Updates the `scripts` section and dependencies in `package.json`.
3. **Irreversible:** Once ejected, you can't revert back to the standard Create React App setup.

Ejecting is useful for advanced customizations but is irreversible. Use it only if you need deep customization that isn't possible with the default setup.


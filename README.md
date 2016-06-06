# React Boilerplate

Boilerplate starter kit for a React web app. Included components:

- react, react-dom, react-router, global for rendering frontend
- firebase for backend
- express, body-parser, nodemon for server
- webpack for production builds, webpack-dev-server for dev builds, with config files
- babel-core, babel-loader, babel-preset-es2015, babel-preset-react for transpilation
- eslint, eslint-plugin-react, babel-eslint for linting
- mocha, chai for testing
- npm scripts for builds, tests, Travis CI, and Heroku
- .babelrc, .eslintrc.json, and .travis.yml config files included
- Includes basic test spec file and basic files to render a landing page

## Getting Started

Clone the repo, delete the `.git` folder and run `git init` to start as a fresh project. Change `package.json` as needed to reflect new name of the project.

### Development & Scripts

Edit files in `./app/` folder, this is the entry point for the Webpack bundle. Built bundle will be written to `./dist` folder.

If any changes need to be made to the main html wrapper at `./index.html`, they will be copied to the `./dist` folder on build.

Start development server with live Webpack incremental builds:
```
npm run serve
```

Start production server and build Webpack bundle:
```
npm run serve:dist
```

Start production server only:
```
npm start
```

Run Mocha/Chai Unit Tests:
```
npm run mocha
```
To run tests continuously:
```
npm run mocha:watch
```

Run ESLint:
```
npm run lint
```

Run both unit tests and linting, same as Travis CI:
```
npm test
```

## Author

* Cliff Saporta Cheng - [ccfcheng](https://github.com/ccfcheng)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

# webpack-boilerplate
Webpack boilerplate for new projects.

## terminal: 
  - `npm init -y`
  - `npm install eslint -D`
  - `npm init @eslint/config`
  - `npm install webpack webpack-cli webpack-dev-server -D`
  - `npm install css-loader style-loader -D`
  - `npm install gh-pages -D`
  - `npm install jest -D`

## package.json scripts:

    "test": "jest",
    
    "watch": "jest --watch *.js",
    
    "build": "webpack",

    "start": "webpack serve --open",

    "predeploy": "npm run build",

    "deploy": "gh-pages -d dist"

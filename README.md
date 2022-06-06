# minesweeper

Building Minesweeper Application Using React/Redux Saga

npm init

  test command: jest

npm i typescript -D // -D for dev dependency
// Not using typescript as global dependency. Using binary via npx.

npx tsc --init

//See if everything working properly, create a file called test.ts in src directory
// run => npx tsc ./src/test.ts to see if test.js file created under test.ts. If 
// created then test passed.

//Let's install ESLint as dev dependency

npm install eslint -D

npx eslint --init
  style
  esm
  react
  Yes
  browser
  guide
  airbnb
  JavaScript

  //in .eslint.js file add following to rules section
  rules: {
    quotes: ["error", "double"],
  },

  run => npx eslint ./.eslintrc.js --fix

  






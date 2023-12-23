# repo-template
Template for future projects

# Setting up ESLint
1. npm init --yes
2. npm install eslint --save-dev
3. ./node_modules/.bin/eslint --init
4. ? How would you like to use ESLint? …
  To check syntax only
  To check syntax and find problems
❯ To check syntax, find problems, and enforce code style
5.  What type of modules does your project use? …
  JavaScript modules (import/export)
❯ CommonJS (require/exports)
  None of these
6. ? Which framework does your project use? …
  React
  Vue.js
❯ None of these
7. ? Does your project use TypeScript? › No / Yes (No)
8. ✔ How would you like to define a style for your project? …
❯ Use a popular style guide
  Answer questions about your style
  Inspect your JavaScript file(s)
9. ? What format do you want your config file to be in? …
  JavaScript
  YAML
❯ JSON
10. ? Would you like to install them now with npm? › No / Yes (Yes)

# Setting up webpack
1. npm install webpack
2. npm run build

# Setting up Prettier
1. npm install --save-dev --save-exact prettier
2. npx prettier . --write
3. To check format use: npx prettier . --check

# Setting up eslint-prettier
1. npm install --save-dev eslint-config-prettier
2. In the eslintrc.js file add the following
   {
  "extends": [
    "some-other-config-you-use",
    "prettier"
  ]
}

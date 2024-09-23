# eslint-config-prettier

Turns off all rules that are unnecessary or might conflict with [Prettier].
## Installation

1. Install eslint-config-prettier: as a devdependeices

   ```
   npm install -D eslint
   npm install --save-dev eslint-config-prettier
   ```
2. initialize (init) eslint-config-prettier: as a devdependeices

   ```
   npm init @eslint/config
   or
   npm init @eslint/config@latest
   
   ```
   
## Setup Setting
01. to check syntax, find problems,and enforce code style
2. javaScript modules (import/export)
3. React
4. ?Does your project use Typescript>> No
5. Frontend Project (Browser)//// Backend Project (Node)
6. Use a popular style ( guide )
7. Airbnb:http://
8. JavaScript
9. Would you like to install them now>>> Yes
10. with (npm)

## VS_CODE Extention Installation
01. pretter
2. eslint
## Create Root Directory (.vscode)
#.vscode
#settings.json

















11. Add eslint-config-prettier to your ESLint configuration – either to [eslintrc] or to [eslint.config.js (flat config)].

   - eslintrc: Add `"prettier"` to the "extends" array in your `.eslintrc.*` file. Make sure to put it **last,** so it gets the chance to override other configs.

     <!-- prettier-ignore -->
     ```json
     {
       "extends": [
         "some-other-config-you-use",
         "prettier"
       ]
     }
     ```

   - eslint.config.js (flat config): Import eslint-config-prettier, and put it in the configuration array – **after** other configs that you want to override.

     <!-- prettier-ignore -->
     ```js
     import someConfig from "some-other-config-you-use";
     import eslintConfigPrettier from "eslint-config-prettier";

     export default [
       someConfig,
       eslintConfigPrettier,
     ];
     ```

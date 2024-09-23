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




## Custome Setup For Eslint & Prettier

   - eslintrc: Add a Folder Root Directory `".vscode"` then create a file  `.settings.json.*` file.

     ```json
{
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.formatOnSave": true,
	"[javascript]": {
		"editor.formatOnSave": false
	},
	"[javascriptreact]": {
		"editor.formatOnSave": false
	},
	"editor.codeActionsOnSave": {
		"source.fixAll": true
	},
	"eslint.alwaysShowStatus": true,
	"eslint.validate": [
		"javascript",
		"javascriptreact",
		"typescript",
		"typescriptreact"
	],
	"prettier.useTabs": true,
	"prettier.jsxSingleQuote": false,
	"prettier.tabWidth": 2,
	"prettier.arrowParens": "avoid",
	"prettier.singleQuote": true
}
     ```
##End

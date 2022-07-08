# Employee Tracker

## Purpose
This project is designed give the user the ability to view and manage the departments, roles, and employees in the company so that they can organize and plan the business through a command line interface content management system.

## Why It Doesn't Work
Inquirer is not working for me. I reviewed back to module 9.3 and googled for solutions. Everytime I run `node server.js` I am given an error that requiring the Inquirer package is not supported and to instead change the require of inquirer.js to a dynamic import() which is available in all CommonJS modules. 
### Things I've Tried
- I have tried substituting `import inquirer from inquirer` in place of `const inquirer = require('inquirer');`
- I have tried adding `"type": "module"` to the package.json file.


## Built With
- JavaScript
- Node.js
- express
- Inquirer package (or at least my best attempt at it)
- MySQL2
- console.table package

## Link to Video Submission
[Video] (https://mikak02.github.io/week12Challenge/)

## Screenshot
![Screenshot of website](/db/assets/images/Screenshot.png)
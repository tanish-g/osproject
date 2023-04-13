# osproject

Step 1: Project Setup:

Initializes NPM: Create and Locate your project folder into the terminal & type the command

```npm init -y```
It initializes our node application & makes a package.json file.

Install Dependencies: Locate your root project directory into the terminal and type the command

'''npm install express ejs body-parser'''
To install Express, EJS, and Body Parser as dependencies inside your project

Create Server File: Create an ‘app.js’ file, inside this file require the Express Module, and create a constant ‘app’ for creating an instance of the express module, then set the EJS as the default view engine.

'''const express = require('express');

const app = express();
app.set('view engine', 'ejs');'''

Rearrange Your Directories: It is required to use ‘.ejs’ as an extension for the HTML file instead of ‘.html’ for using EJS inside it. Then you have to move every ‘.ejs’ file in the views directory inside your root directory. EJS is by default looking for ‘.ejs’ files inside the views folder.

Use EJS variable: Inside your updated .ejs file, you have to use EJS Variables to receive values from your server file. You can declare variables in EJS like

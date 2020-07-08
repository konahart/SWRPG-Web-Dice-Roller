# SWRPG-Web-Dice-Roller

A Web App Companion for the SWRPG


# Installation and Setup

1.  First you will need to have NodeJS installed on your machine. You can find the latest version [here](https://nodejs.org/en/)
2.  Click "Clone or Download" at the top of this page. Click "Download Zip" and extract the files.
3.  Next Create a firebase project for the WebApp [here](https://console.firebase.google.com/)
    1.  Click "Add Project"
    2.  Name your project
    3.  From the project console, click "Add Firebase to your web app"
    4.  Copy `var config = {xxxxxxx};` (8 lines total)
    5.  Open src/config.js from from step 2 with a text editor program of your choice.
    6.  Paste `var config = {xxxxxxx};` in space marked "Paste var config = {xxxxxxx}; here"
4.  In your local environment, open command line and navigate to folder from step 2
5.  `$ git update-index --skip-worktree src/config.js`
6.  `$ npm install`
7.  `$ npm install -g firebase-tools`
8.  `$ npm run build`
9.  `$ firebase login`
10.  `$ firebase deploy`
11.  terminal will give you a website to go to

## Run Locally (after previous setup)
`$ npm start`

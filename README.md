# Pug Example

Project:  This project is designed to test Pug.
Author:   Robert Glover
Date:     2018-08-30

## Build Process

1.  mkdir pug-examples
2.  cd routing-examples
3.  git init
4.  npm init -y
5.  Create folders:
    - src
    - public
    - views
6.  Add src/server.js:
    - simple web server
7.  Modify package.json:
    - main: src/server.js
    - start: node src/server.js
8.  Run with npm start (nodemon)

### Note that there is no need to install Node or Express as they have been installed globally.
### Although, if I were going to distribute the App, I would need to install Express locally.

## Git Update Process
1.  Create repo on GitHub with .gitignore file included.
2.  git add .
3.  git commit -a -m "Routing examples"
4.  git remote add origin https://github.com/robertfg/fetch-examples.git
5.  git push --set-upstream origin master

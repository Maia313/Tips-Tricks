#### GET VERSION
```npm
npm -v (or --version)
```
#### GET HELP
```npm
npm help
npm
```
#### CREATE PACKAGE.JSON
```npm
npm init
npm init -y (or --yes)
```
#### SET DEFAULTS
```npm
npm config set init-author-name "YOUR NAME"
npm set init-license "MIT"
```
#### GET DEFAULTS
```npm
npm config get init-author-name
npm get init-license
```
#### REMOVE DEFAULTS
```npm
npm config delete init-author-name
npm delete init-license
```
#### INSTALLING LOCAL PACKAGES
```npm
npm install lodash --save (or npm install --save lodash)
npm install moment --save
npm install gulp gulp-sass --save-dev
```
#### MOVE TO ANOTHER FOLDER
```npm
npm install
npm install --production
```
#### REMOVING MODULES
```npm
npm uninstall gulp-sass --save-dev
npm remove gulp --save-dev
```
#### INSTALL CERTAIN VERSIONS
```npm
npm install lodash@4.17.3 --save
```
#### UPDATE
```npm
npm update lodash --save
```
#### INSTALL GLOBAL MODULE
```npm
npm install -g nodemon
npm install -g live-server
```
#### RUN NODEMON
```npm
nodemon
```
#### FIND ROOT FOLDER
```npm
npm root -g
```
#### REMOVE GLOBAL PACKAGES
```npm
npm remove -g nodemon
```
#### LISTING PACKAGES
```npm
npm list
npm list --depth 0
npm list --depth 1
```
#### INSTALL LIVE-SERVER LOCALLY
```npm
npm install live-server --save-dev
```
#### NPM SCRIPT
```npm
"scripts": {
    "start": "node index.js",
    "dev": "live-server"
  },
```

# Grunt-boiler-plate
This is an boiler plate for web-development 


## Basic Template
```
tree

.
├── htdocs (This is an symlink to /var/www/html)
│   ├── css
│   ├── index.php
│   └── js
└── project
    ├── css
    │   └── style.css
    ├── grunt
    │   ├── dist
    │   ├── Gruntfile.js
    │   ├── package.json
    │   └── package-lock.json
    ├── js
    │   └── app.js
    └── scss

11 directories, 6 files
```

Note:

You can have as much files and folders you want in the `css` and `js` folders of the project folder.

## Setup

Install node and ruby
```
sudo apt update
sudo apt install nodejs
sudo apt install ruby-full
sudo gem install sass

node -v // to verify the installation
npm -v
gem list
```
Install grunt and grunt-cli
```
npm i grunt // run this from the /project/grunt folder.
sudo npm install -g grunt-cli

grunt --version // to verify the installation
```
Node Initialisation
```
npm init // run this from the /project/grunt folder. (Answer all the questions)
```
install all the dependencies
```
npm install grunt-contrib-watch --save-dev
npm install grunt-contrib-concat --save-dev
npm install grunt-contrib-obfuscator --save-dev
npm install javascript-obfuscator --save-dev
npm install grunt-contrib-cssmin --save-dev
npm install grunt-contrib-uglify --save-dev
npm install grunt-contrib-sass --save-dev
```
## Testing

Create few files in the js and css file.
then run `grunt` command from `/project/grunt` folder.



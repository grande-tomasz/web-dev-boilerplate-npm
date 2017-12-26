# Boilerplate package for building front-end web projects

The purpose for creating this package was to prepare a good starting point and automation tool for building front-end web projects.

## Usage
1. Download this repository and change its folder name.
2. Install all modules from devDependencies using `npm install` command (requires Node.js installed).
3. Adjust package.json file to your needs and change the description in README.md file.
4. Enjoy!

## Contents
Below there are descriptions of all main tasks with their subtasks

**build** – builds the whole docs folder and compiles all the required files
* **rm-rf** – removes files from docs directory
* **mkdir-p** - creates new directories used in docs
* **cp-r** - copies files which will not be processed to docs directory
* **sass** - compiles scss files to css
* **autoprefixer** - adds vendor prefixes to css rules
* **minify:html** - minifies index.html document based on the default configuration of [HTML Minifier]("https://kangax.github.io/html-minifier/")
* **minify:css** - minifies style.css file
* **minify:js** - minifies JavaScript files
* **minify:img** - compresses images

**watch** – watches for changes and shows them directly in the browser
* **watch:sass** – compiles scss files to css and adds vendor prefixes to css rules when scss files change
* **browse:src** - browses source files and synchronizes a browser with their changes

**edit** - opens new instance of Visual Studio Code with all the default project files

**postinstall** – runs build, edit and watch tasks after installing the dependencies of the package to automate its use

## Development dependencies

The package is dependent on the following modules:
* <a href="http://www.npmjs.com/package/rimraf" target="_blank">**rimraf**</a>
* <a href="http://www.npmjs.com/package/mkdirp" target="_blank">**mkdirp**</a>
* <a href="http://www.npmjs.com/package/cpr" target="_blank">**cpr**</a>
* <a href="http://www.npmjs.com/package/postcss-cli" target="_blank">**postcss-cli**</a>
* <a href="http://www.npmjs.com/package/node-sass" target="_blank">**node-sass**</a>
* <a href="http://www.npmjs.com/package/autoprefixer" target="_blank">**autoprefixer**</a>
* <a href="http://www.npmjs.com/package/html-minifier" target="_blank">**html-minifier**</a>
* <a href="http://www.npmjs.com/package/clean-css" target="_blank">**clean-css**</a>
* <a href="http://www.npmjs.com/package/uglify-js" target="_blank">**uglify-js**</a>
* <a href="http://www.npmjs.com/package/imagemin-cli" target="_blank">**imagemin-cli**</a>
* <a href="http://www.npmjs.com/package/browser-sync" target="_blank">**browser-sync**</a>
* <a href="http://www.npmjs.com/package/onchange" target="_blank">**onchange**</a>
* <a href="http://www.npmjs.com/package/npm-run-all" target="_blank">**npm-run-all**</a>

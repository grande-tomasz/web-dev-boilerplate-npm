<h1>Boilerplate package for building front-end web projects</h1>

<h2>The Purpose</h2>
<p>The purpose for creating this package was to prepare a good starting point and automation tool for building front-end web projects.</p>

<h2>Contents</h2>
<p>The package focuses on two main tasks which consist of some smaller ones.</p>

<b>build</b> – builds the whole distribution folder and compiles all the required files
<ul>
  <li><b>rm-rf</b> – removes files from distribution directory</li>
  <li><b>mkdir-p</b> - creates new directories used in distribution</li>
  <li><b>cp-r</b> - copies files which will not be processed to distribution directory</li>
  <li><b>sass</b> - compiles scss files to css</li>
  <li><b>autoprefixer</b> - adds vendor prefixes to css rules</li>
  <li><b>minify:html</b> - minifies index.html document based on the default configuration of <a href="https://kangax.github.io/html-minifier/" target="_blank">HTML Minifier</a></li>
  <li><b>minify:css</b> - minifies style.css file</li>
  <li><b>minify:js</b> - minifies JavaScript files</li>
  <li><b>minify:img</b> - compresses images</li>
</ul>

<b>watch</b> – watches for changes and shows them directly in the browser
<ul>
  <li><b>watch:sass</b> – compiles scss files to css and adds vendor prefixes to css rules when scss files change</li>
  <li><b>browse:src</b> - browses source files and synchronizes a browser with their changes</li>
</ul>

<b>postinstall </b> – runs build and watch tasks after installing the dependencies of the package to automate its use

<h2>Development dependencies</h2>

<p>The package is dependent on the following modules:</p>
<ul>
  <li><a href="http://www.npmjs.com/package/rimraf" target="_blank"><b>rimraf</b></a></li>
  <li><a href="http://www.npmjs.com/package/mkdirp" target="_blank"><b>mkdirp</b></a></li>
  <li><a href="http://www.npmjs.com/package/cpr" target="_blank"><b>cpr</b></a></li>
  <li><a href="http://www.npmjs.com/package/postcss-cli" target="_blank"><b>postcss-cli</b></a></li>
  <li><a href="http://www.npmjs.com/package/node-sass" target="_blank"><b>node-sass</b></a></li>
  <li><a href="http://www.npmjs.com/package/autoprefixer" target="_blank"><b>autoprefixer</b></a></li>
  <li><a href="http://www.npmjs.com/package/html-minifier" target="_blank"><b>html-minifier</b></a></li>
  <li><a href="http://www.npmjs.com/package/clean-css" target="_blank"><b>clean-css</b></a></li>
  <li><a href="http://www.npmjs.com/package/uglify-js" target="_blank"><b>uglify-js</b></a></li>
  <li><a href="http://www.npmjs.com/package/imagemin-cli" target="_blank"><b>imagemin-cli</b></a></li>
  <li><a href="http://www.npmjs.com/package/browser-sync" target="_blank"><b>browser-sync</b></a></li>
  <li><a href="http://www.npmjs.com/package/onchange" target="_blank"><b>onchange</b></a></li>
  <li><a href="http://www.npmjs.com/package/npm-run-all" target="_blank"><b>npm-run-all</b></a></li>
</ul>

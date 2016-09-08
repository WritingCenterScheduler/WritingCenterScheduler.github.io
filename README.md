# WritingCenterScheduler.github.io
The COMP523 website repository.

##Sprint 1 Development Branch

# SWE Fall 2016
The source of the website for SWE 2016.

## Setup
Install some stuff:
```
gem install sass
brew install node
npm install
```
Optionally, install gulp cli tools.
```
npm install --global gulp-cli
```

## Development
This website uses [gulp](http://gulpjs.com) as a build tool to compile assets and deploy the site. Here's the stuff you need to know:
```
gulp compile	# Compiles the site into /out
gulp watch		# Compiles the site and starts a server (--port defaults to 8000)
```

There are also other commands if you want to compile individual types of assets:
```
gulp jade		# Compiles jade/*.jade and puts them in out/ as HTML files
gulp scss		# Compiles and minifies scss/*.scss and puts them in out/ as CSS files
gulp js			# Concats all files in js/**/* and puts it in out/main.js
gulp images 	# Compresses img/**/* and puts everything in out/img
gulp static		# Moves static/**/* to out/
```

### Naming Conventions
In most directories, filenames that begin with underscores are partials. They are not compiled or placed in `/out`, but they are often loaded by scss, jade, or js files.

For javascript, the dependency order is denoted by the number of underscores: files with two underscores are loaded first (i.e. `__*.js`, then files with one underscore (`_*.js`), then files without any underscore (`*.js`).

## Tests
None yet

## Deployment
Gulp also handles our deployments. Once you've submitted a pull request and had your code reviewed, merge it into `master`and run 
`gulp deploy`
This will compile assets and push them to the `gh-pages` branch.

## Requirements
* Node.js v4.*
* NPM v2.*
* Sass >= 3.4
* Everything in `package.json`
>>>>>>> master

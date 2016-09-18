# Starter gulpfile.js for Front-End Development
This is a common, reusable Gulp file tailored towards front-end focused projects. It can be used as-is or customised to fit your development environment.


## Features

**Clean**:
Deletes 'dist' directory

**Images**:
Optimise PNGs, JPGs, SVGs, and GIFs

**SVG Sprite**:
Merge SVGs into a sprite. One sprite is generated per directory within 'img/vectors'

**Javascript**:
JSHint and minify javascript files

**CSS**:
Clips empty files from the stream, sourcemaps (if not production), autoprefixes css, combines media queries, minifies css


## Getting Started
1. Clone the project / Download the zip.
```
git clone git@github.com:JakeCobley/gulpfile.js.git projectname
```
2. Navigation to the working directory
```
cd projectname
```
3. Install npm modules
```
npm i
```
4. Update variables, paths, folders, extensions etc at top of the gulpfile.js
file to suite your project.


## NPM Tasks
* `$ npm run watch` - Builds assets and watches directories for changes.
* `$ npm run build` - Builds all assets.
* `$ npm run build:production` - Builds all assets for production (Minified CSS and JavaScript, compressed images etc).


## Example Project Structure
*This can be easily changed to suit your project.*
```
+-- dist/
|   +-- css
|   +-- img
|   |   +-- vectors
|   +-- js
+-- node_modules/
+-- src/
|   +-- img
|   |   +-- vectors
|   +-- js
|   +-- scss
+-- .editorconfig
+-- .gitignore
+-- gulpfile.js
+-- LICENCE.md
+-- package.json
+-- README.md
```

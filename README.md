# Starter gulpfile.js for Front-End Development
This is a common, reusable Gulp file tailored towards front-end focused
projects. It can be used as-is or customised to fit your development
environment.

## Features

**Clean**:
Deletes 'dist' directory

**Images**:
Optimise PNGs, JPGs, SVGs, and GIFs

**SVG Sprite**:
Merge SVGs into a sprite. One sprite is generated per directory within
'img/vectors'

**Javascript**:
JSHint and minify javascript files

**CSS**:
Clips empty files from the stream, sourcemaps (if not production), autoprefixes
css, combines media queries, minifies css

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

### NPM Scripts
* `$ npm run watch` - Builds assets and watches directories for changes.
* `$ npm run build` - Builds all assets.
* `$ npm run build:production` - Builds all assets for production (Minified CSS
  and JavaScript, compressed images etc).

### Example Project Structure
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

## Bugs and feature requests

Have a bug or a feature request? Please first read the [contributing guidelines](https://github.com/jakecobley/gulpfile.js/blob/next/.github/CONTRIBUTING.md)
document and search for existing and closed issues. If your problem or idea is
not addressed yet, please open a [new issue](https://github.com/jakecobley/gulpfile.js/issues).

## Contributing

Please read through our [contributing guidelines](https://github.com/jakecobley/gulpfile.js/blob/next/.github/CONTRIBUTING.md).
Included are directions for opening issues, coding standards, and notes on
development.

Editor preferences are available in the editor config for easy use in common
text editors. Read more and download plugins at http://editorconfig.org.

## Versioning

This project is maintained under the [Semantic Versioning guidelines](http://semver.org/).
Sometimes we screw up, but we'll adhere to those rules whenever possible.

See the [Releases](https://github.com/jakecobley/gulpfile.js/releases) section
of our GitHub project for changelogs for each release.

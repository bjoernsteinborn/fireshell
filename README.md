# FireShell

Quick-start for rapid project prototyping.

+ Bower for third-party dependancies
+ Grunt for task management
+ SASS
+ Autoprefixer for CSS vendor compatibility
+ Image optimization
+ Separated `src/` and `app/` directories for cleaner builds

## Getting Started

Create an export of Fireshell for your new project:

#### `$ grunt new[:name]`

Copies all the required files for a clean install for setting up a new project. This is the only task executed within the current Fireshell directory.

Now `cd` into your new project directory and run the init script:

#### `new-project/ $ sudo bash ./init.sh`

This should install all the required files (npm & bower) and copy any initial bower dependencies to get you started.

## Grunting

Below are a sample of the Grunt tasks available within your new project:

#### `$ grunt`

Creates a new development-ready environment and beings watching all files for changes.

#### `$ grunt css[:dist]`

Generate CSS using development settings and output statistics.

#### `$ grunt js[:dist]`

Generates a new Modernizr build and minifies all specified JS files. 

#### `$ grunt build[:dist]`

Creates a production-ready environment of your project. 

+ Cleans the `app/` directory
+ Copies all specified Bower files
+ Copies and optimises all images
+ minifies and uglifies all JS while also creating a new Modernizr build
+ Generates CSS and uses Autoprefixer for browser compatibility

## Credits

This FireShell was originally built by [Todd Motto](//github.com/toddmotto) and it's contributors; [Jean-Philippe Sirois](//github.com/jpsirois), [Noah Bass](//github.com/noahbass), [Bernard Chhun](//github.com/bchhun), [Chris Missal](//github.com/ChrisMissal), [Mihai Ionut Vilcu](//github.com/ionutvmi), [Octavio Amuchastegui](//github.com/octavioamu).

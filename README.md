# RPG-Web-Components
An AoR-themed set of AngularJS directives and components

Please view the examples at: https://tk20466.github.io/

Live example:  http://swrpg.sarah-bailey.com/

**Current Version**: 0.9.5

**Usage**: just include the module in your application module after referencing AngularJS and the included javascript/css file.

    var app = angular.module("myApp", ["swaor"]);

**Building**: Make sure you have the following NPM packages installed:
 * [gulp](https://www.npmjs.com/package/gulp)
 * [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)
 * [gulp-uglifycss](https://www.npmjs.com/package/gulp-uglifycss)
 * [gulp-concat](https://www.npmjs.com/package/gulp-concat)
 * [gulp-angular-templatecache](https://www.npmjs.com/package/gulp-angular-templatecache)
 * [gulp-htmlmin](https://www.npmjs.com/package/gulp-htmlmin)

Then run the following two commands in your command line

    gulp templates
    gulp release

your files will be output to a /releases folder

To-do:

* Finish documentation
* Minion group size handling
* live-tracker for wounds/strain/group size
* Ranged/Melee defense box
* Better equipment management
* IE11 and Firefox support
* WYSIWYG editor with preview

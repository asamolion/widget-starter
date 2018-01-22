# widget-starter
Starter kit for creating widgets using Pug, Sass and ES6

## Introduction
The main workflow consists of a few simple Gulp.js tasks

The source files are contained in the `src` folder. And everything is configured to work using only a few gulp tasks.

```
$ gulp html
```
Compiles `index.pug` in `src` folder to HTML and puts it in the `build` directory

```
$ gulp css
```
Compiles `style.scss` in `src` folder to CSS and puts it in the `build` directory

```
$ gulp js
```
Compiles `app.js` (es6) in `src` folder to JS (es5) and puts it in the `build` directory

```
$ gulp watch
```
Starts a development server in the `build` directory

```
$ gulp minify
```
Takes the HTML, CSS and JS files in the build directory and creates a single HTML file with all the CSS and JSS embedded into it in the `prod` folder

And finally

```
$ gulp
```
Just running gulp runs all of the above in sequence (skipping `watch` of course)


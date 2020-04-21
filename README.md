# Marketing Agency one page template - ARCHIVED


![Mockup demo](screenshots/pic.jpg)


## Contents

- 

## Folder and file structure

## Requirements

- [Node.js](http://nodejs.org/)
- Build sytem: [Grunt](http://gruntjs.com/) or [Gulp](http://gulpjs.com/)
- Optionally:
  * [Editorconfig](http://editorconfig.org/)

#### Editorconfig



## How to start

If you haven't used [Gulp](http://gulpjs.com/) before, be sure to check out the [Getting Started]([https://github.com/gulpjs/gulp/blob/master/docs/README.md](https://gulpjs.com/docs/en/getting-started/quick-start)) guide, also check these [recips](https://github.com/gulpjs/gulp/tree/master/docs/recipes#recipes)

Before start you need to have installed _npm_ , as well as _gulp_ globally.

**A few simple steps to start:**
* Install dependencies from `package.json` by running: `npm install`.
* Run tasks from the list below and start devevelopment!
* Edit general settings in `dev/data/config.json` See [Site configuration](#site-configuration) section

## Site configuration

This boilerplate uses Pug templates with external data configs.
Main settings can be found in `dev/data/config.json` file. And they're available for usage in templates with `config.key-name`

## Tasks

Here comes groups ofgulp tasks with some explanations

#### Cleanup

Remove placeholders from work directories.
Gulp: `gulp cleanup`

* Remove gitkeep files

#### Dev

Dev task with static server.
Gulp: `gulp dev`

* Bundle javascripts
* Compile Sass stylesheets
* Add vendor prefixes in css
* Combine media queries in css files
* Compile Pug templates
* Sync helpers and other assets
* Sync fonts
* Sync images
* Run BrowserSync static server with live reload using
* Watch for changes and run dev task


#### Build

Build task.
Gulp: `gulp build`

* Minify images
* Minify javascript files
* Minify stylesheets
* Minify html
* Run BrowserSync static server


#### Rebuild

Regenerate and build project by running all tasks.
Gulp: `gulp rebuild`

* Bundle javascripts
* Compile Sass stylesheets
* Add vendor prefixes in css
* Combine media queries in css files
* Compile Pug templates
* Sync helpers and other assets
* Sync fonts
* Sync images
* Minify images
* Minify javascript files
* Minify stylesheets
* Minify html


#### Server

Run server without watching for changes.
Gulp: `gulp server`

* Run BrowserSync static server


## Live reload

This project uses BrowserSync as static server with enabled and configured live reload option.

## License
[MIT](https://github.com/website-templates/marketing-agency_one-page-template/blob/master/LICENSE.md)

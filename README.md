
Contains gulpfile configuration for beginning web development using HTML, (S)CSS, JS with Babel

### Requirements

This requires the following dependencies:

- [Node.js](https://nodejs.org/)
- [Gulp JS](https://gulpjs.com/)

## First steps

1. Clone or download this repository to your machine
2. Open a terminal into your current project and type this command:
- `$ npm install` - installation of all dev dependencies into your current folder
3. To use gulp commands see gulpfile.js file or type in terminal:
```sh
$ gulp watch
$ gulp build
```

- `gulp watch` : for instant browser reload, compile scss->css, transpile es6->es5, watch html, scss, images, fonts changes
- `gulp build` : a mix of ```gulp watch``` command but with creation of dist folder which contains final bundle of your watched files


### How to work in HTML files
I have used Panini library for building up HTML documents. So, please check out Panini docs if you don't have experience working with it yet.
You may notice an `index.html` document inside src folder. That is main file. However, if you have a content page you may create a new document
with the name `content.html` and paste into next code:
- `---
	layout: default
	title: Content
	---`

The title represents the title of your content.html document and the layout represents default layout pulled by content.html in this case. 
However it may be replaced with other layout you create into `src/layouts` folder
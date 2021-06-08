# ELMAK BOOTSTRAP + GULP STARTER TEMPLATE

### Note

Changes should be commited to `src` files only.

### Features

The template is built with Sass and Gulp build system with these features:

-	Handlebars HTML templates with Panini – It compiles a series of HTML pages using a common layout. These pages can also include HTML partials, external Handlebars helpers, or external data as JSON or YAML.
-	Sass compilation, prefixing with autoprefixer, and javaScript concatenation
-	Built-in BrowserSync server - will automatically reload your page when files are changed. It runs continuously and defaults to localhost.
-	For production builds - CSS compression, JavaScript compression, Image compression and more.

### Installing:

- Install all node packages: `npm install`
- Run `gulp development`
- Your site is now viewable at this URL: http://localhost:3000
- To create compressed, production-ready assets run `gulp production`. This will delete everything in the dist folder and recreate all of your compilied files. 

### Folder Structure:

- `dist/` - compiled distribution files
- `node_modules` - front-end dependencies
- `src/` - contains all of your core, working files—static assets, pages, templates, etc
- `src/assets/` - scss files, JS files, images, and fonts
- `src/data/` - external data (JSON or YAML)
- `src/layouts/` - HTML layouts templates
- `src/pages/` - site pages
- `src/partials/` - handlebars partials files.
- `gulpfile.js` - all task definitions
- `package.json` - handles the project dependencies
- `.htmllintrc` - handles the HTML lint rules
- `.sass-lint.yml` - handles the SCSS lint rules

### Gulp Plugins:
- [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer)
- [gulp-compile-handlebars](https://www.npmjs.com/package/gulp-compile-handlebars)
- [gulp-concat](https://www.npmjs.com/package/gulp-concat)
- [gulp-cssmin](https://www.npmjs.com/package/gulp-cssmin)
- [gulp-html-replace](https://www.npmjs.com/package/gulp-html-replace)
- [gulp-htmllint](https://www.npmjs.com/package/gulp-htmllint)
- [gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin)
- [gulp-pretty-html](https://www.npmjs.com/package/gulp-pretty-html)
- [gulp-remove-code](https://www.npmjs.com/package/gulp-remove-code)
- [gulp-remove-logging](https://www.npmjs.com/package/gulp-remove-logging)
- [gulp-rename](https://www.npmjs.com/package/gulp-rename)
- [gulp-sass](https://www.npmjs.com/package/gulp-sass)
- [node-bourbon](https://www.npmjs.com/package/node-bourbon)
- [gulp-sass-lint](https://www.npmjs.com/package/gulp-sass-lint)
- [gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps)
- [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)
- [gulp-newer](https://www.npmjs.com/package/gulp-newer)
- [gulp-jshint](https://www.npmjs.com/package/gulp-jshint)
- [gulp-gulp-gh-pages](https://www.npmjs.com/package/gulp-gh-pages)
- [gulp-babel](https://www.npmjs.com/package/gulp-babel)
- [panini](https://www.npmjs.com/package/panini)
- [run-sequence](https://www.npmjs.com/package/run-sequence)
- [ansi-colors](https://www.npmjs.com/package/ansi-colors)
- [fancy-log](https://www.npmjs.com/package/fancy)


### Additional Resources:
- [Sass: Syntactically Awesome Style Sheets](http://sass-lang.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Handlebars](http://handlebarsjs.com/)
- [Panini](https://github.com/zurb/panini)
- [Gulp](https://gulpjs.org/getting-started)

### Documentation:
https://godwinelitcha.com/guides/frontend/sass-bts-integration


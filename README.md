# Codeman SCSS

CSS on its own can be fun, but stylesheets are getting larger, more complex, and harder to maintain. This is where a preprocessor can help. Sass has features that don't exist in CSS yet like nesting, mixins, inheritance, and other nifty goodies that help you write robust, maintainable CSS.

## Preprocessing

You can also watch individual files or directories with the --watch flag. The watch flag tells Sass to watch your source files for changes, and re-compile CSS each time you save your Sass. If you wanted to watch (instead of manually build) your input.scss file, you'd just add the watch flag to your command, like so:

```bash
sass --style compressed --watch scss/app.scss:css/styles.min.css
sass --style compressed --watch scss/app.scss:css/styles.min.css & disown
```

# Installation

If you use Node.js, you can also install Sass using npm by running

```bash
npm install -g sass
```
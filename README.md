# Webpack

This is a project to learn everything about webpack and to serve as a reference.

## Loaders

### Babel
* `babel-loader` - teaches babel how to work with webpack
* `babel-core` - takes in code, parses it, and generates output files
* `babel-preset-env` - ruleset telling what pieces of ES2015/6/7 to look for and convert to ES5

### CSS
* `css-loader` - tells webpack how to handle with CSS imports
* `style-loader` - adds CSS to HTML docs
* `extract-text-webpack-plugin` - places CSS in seperate file in build

### Images
* `image-webpack-loader` - compresses images
* `url-loader` - if it's a small image then include in bundle, if not, then place image in build directory
# React + Webpack

## Instructions

1. Initializing npm project
   1. npm init -y
2. Setting up webpack
   1. npm i --save-dev webpack webpack-cli
3. Setting up Html Webpack Plugin
   1. npm i --save-dev html-webpack-plugin
4. Setting up Webpack Dev Server
   1. npm i --save-dev webpack-dev-server
   2. It appears that webpack-dev-server doesn't serve the content from the dist folder
5. Configuring css loaders in webpack
   1. npm i --save-dev style-loader css-loader
      1. In this way css is inserted in the bundle.js
   2. npm i --save-dev mini-css-extract-plugin
      1. Using this plugin we are extracting css files from bundle.js
6. Adding jQuery using webpack
   1. npm i jquery

## Links

1. https://blog.jakoblind.no/
2. [Configuring CSS and CSS Modules](https://blog.jakoblind.no/css-modules-webpack/)
3. https://github.com/webpack-contrib/css-loader#recommend

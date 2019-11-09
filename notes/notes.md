git init
yarn init
yarn add -D @babel/core @babel/preset-env @babel/preset-react babel-loader css-loader webpack webpack-cli style-loader webpack-dev-server --->>>>
webpack-merge



yarn add react react-dom

const webpack = require('');
const merge = require('webpack-merge');
const baseWebpackConfig = require('./webpack.base.conf');
const CopyWebpackPlugin = require('copy-webpack-plugin');

webpack-merge
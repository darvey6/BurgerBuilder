# BurgerBuilder

A Burger Building App made from using React

# Setup

\*\*Note must eject project and edit webpack.config.dev.js + webpack.config.prod.js. in config folder
To eject project run: npm run eject

Under test: /\.css\$/ code should have

test: /\.css\$/,
use: [
require.resolve("style-loader"),
{
loader: require.resolve("css-loader"),
options: {
importLoaders: 1,
modules: true,
localIdentName: "[name]**[local]**[hash:base64:5]"
}

# PropTypes Package

used prop type package, to use run:
npm install --save prop-types

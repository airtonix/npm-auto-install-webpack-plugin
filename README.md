# npm-auto-install-webpack-plugin
> Auto installing missing dependencies in package.json before webpack compilation step

[![Version][npm-image]][npm-url] [![Travis CI][travis-image]][travis-url] [![Quality][codeclimate-image]][codeclimate-url] [![Coverage][codeclimate-coverage-image]][codeclimate-coverage-url] [![Dependencies][gemnasium-image]][gemnasium-url] [![Gitter][gitter-image]][gitter-url]


## Installation

```sh
npm i --save npm-auto-install-webpack-plugin
```

## Usage

```js
// webpack.config.babel.js
import NpmAutoInstallWebpackPlugin from "npm-auto-install-webpack-plugin";

export default {
  plugins: [
    new NpmAutoInstallWebpackPlugin(),
  ],
};
```


## Options

```js
new NpmAutoInstallWebpackPlugin(options)
```

### options.autoInstall

Auto install missing dependencies with `npm install` command.

* Default: `true`


## Contributing

[![devDependency Status][david-dm-image]][david-dm-url]

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


[npm-image]: https://img.shields.io/npm/v/npm-auto-install-webpack-plugin.svg?style=flat-square
[npm-url]: https://www.npmjs.org/package/npm-auto-install-webpack-plugin

[travis-image]: https://img.shields.io/travis/tomchentw/npm-auto-install-webpack-plugin.svg?style=flat-square
[travis-url]: https://travis-ci.org/tomchentw/npm-auto-install-webpack-plugin
[codeclimate-image]: https://img.shields.io/codeclimate/github/tomchentw/npm-auto-install-webpack-plugin.svg?style=flat-square
[codeclimate-url]: https://codeclimate.com/github/tomchentw/npm-auto-install-webpack-plugin
[codeclimate-coverage-image]: https://img.shields.io/codeclimate/coverage/github/tomchentw/npm-auto-install-webpack-plugin.svg?style=flat-square
[codeclimate-coverage-url]: https://codeclimate.com/github/tomchentw/npm-auto-install-webpack-plugin
[gemnasium-image]: https://img.shields.io/gemnasium/tomchentw/npm-auto-install-webpack-plugin.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/tomchentw/npm-auto-install-webpack-plugin
[gitter-image]: https://badges.gitter.im/Join%20Chat.svg
[gitter-url]: https://gitter.im/tomchentw/npm-auto-install-webpack-plugin?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[david-dm-image]: https://img.shields.io/david/dev/tomchentw/npm-auto-install-webpack-plugin.svg?style=flat-square
[david-dm-url]: https://david-dm.org/tomchentw/npm-auto-install-webpack-plugin#info=devDependencies


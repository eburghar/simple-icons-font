<p align="center">
<img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/simpleicons.svg#gh-light-mode-only" alt="Simple Icons" width=70><img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/assets/readme/simpleicons-white.svg#gh-dark-mode-only" alt="Simple Icons" width=70>
<h3 align="center">Simple Icons: <em>Icon font</em></h3>
<p align="center">
Free SVG icon font for popular brands. See them all on one page at <a href="https://simpleicons.org">SimpleIcons.org</a>. Contributions, corrections & requests can be made on GitHub.</p>
</p>

<p align="center">
<a href="https://github.com/simple-icons/simple-icons-font/actions?query=workflow%3AVerify+branch%3Adevelop"><img src="https://img.shields.io/github/workflow/status/simple-icons/simple-icons-font/Verify/develop?logo=github" alt="Build status" /></a>
<a href="https://www.npmjs.com/package/simple-icons-font"><img src="https://img.shields.io/npm/v/simple-icons-font?logo=npm" alt="NPM version" /></a>
<a href="https://packagist.org/packages/simple-icons/simple-icons-font"><img src="https://img.shields.io/packagist/v/simple-icons/simple-icons-font?logo=packagist&logoColor=white" alt="Build status" /></a>
</p>

## Setup

> :information_source: We ask that all users read our [legal disclaimer](https://github.com/simple-icons/simple-icons/blob/master/DISCLAIMER.md) before using icons from Simple Icons.

### CDN Setup

The font can be served from a CDN such as [JSDelivr][jsdelivr-link] or [Unpkg][unpkg-link]. Simply use the `simple-icons-font` NPM package and specify a version in the URL like the following:

#### JSDeliver

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/simple-icons-font@v5/font/simple-icons.min.css" type="text/css">
```

#### Unpkg

```html
<link rel="stylesheet" href="https://unpkg.com/simple-icons-font@v5/font/simple-icons.min.css" type="text/css">
```

These examples use the latest major version. This means you won't receive any updates following the next major release. You can use `@latest` instead to receive updates indefinitely. However this may cause an icon to disappear if it has been removed in the latest version.

### Node Setup <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/nodedotjs.svg#gh-light-mode-only" alt="Node" align=left width=24><img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/assets/readme/nodedotjs-white.svg#gh-dark-mode-only" alt="Node" align=left width=24>

The font is also available through our npm package. To install, simply run:

```shell
npm install simple-icons-font
```

After installation, the icons font and stylesheet font can be found in `node_modules/simple-icons-font/font`. You can use your favorite bundling tool to include them into your project.

### PHP Setup <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/php.svg#gh-light-mode-only" alt="Php" align=left width=24 height=24><img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/assets/readme/php-white.svg#gh-dark-mode-only" alt="Php" align=left width=24 height=24>

The font is also available through our Packagist package. To install, simply run:

```shell
composer require simple-icons/simple-icons-font
```

The font can then be used by linking to the stylesheet in your HTML or PHP file (see example in [Manual Setup](#manual-setup)).

### Manual Setup

You can also [download the latest version of the package][latest-release] and copy the content of the `font` folder into your project. Then, reference the CSS file using a `link` tag in your HTML:

```html
<link rel="stylesheet" href="/path/to/simple-icons.min.css" type="text/css">
```

## Usage

Use any of the icons available in simple-icons by adding the following classes to a node in your HTML. Use the `si--color` class to apply the brand's color to the icon.

```html
<i class="si si-[ICON NAME]"></i>
<i class="si si-[ICON NAME] si--color"></i>
```

Where `[ICON NAME]` is replaced by the icon name, for example:

```html
<i class="si si-simpleicons"></i>
<i class="si si-simpleicons si--color"></i>
```

In this example we use the `<i>` tag, but any inline HTML tag should work as you expect.

[latest-release]: https://github.com/simple-icons/simple-icons-font/releases/latest
[jsdelivr-link]: https://www.jsdelivr.com/package/npm/simple-icons-font/
[unpkg-link]: https://unpkg.com/browse/simple-icons-font/

[![Normalize-OpenType.css wordmark](wordmark.svg)](https://github.com/kennethormandy/normalize-opentype)

***

# Normalize-OpenType.css

Add sound OpenType defaults to [Normalize.css](https://github/necolas/normalize.css). Read about it in [Font-feature-settings’ five stages of greif, or introducing Normalize-OpenType.css](http://kennethormandy.com/journal/normalize-opentype-css).

<!-- Etc. What font feature settings is, why the cascading isn’t there, how this helps. -->

## Installation

<!-- Here’s where you write really fantastic instructions that helps people who may or may not even understand what Git is, use your project. For example, your sentences should probably be better than that one. -->

#### With npm

```
npm install kennethormandy/normalize-opentype.css
```
<!--

### With Component

```bash
component install kennethormandy/normalize-opentype.css
```

### With Bower

```bash
bower install normalize-opentype.css
```

-->

## Examples

Though technically Normalize-OpenType.css is not dependent on Normalize.css, the intent expectation is that the former would not be used without the latter. If you’re dropping in stylesheets:

```html
<link src="css/normalize.css" rel="stylesheet" />
<link src="css/normalize-opentype.css" rel="stylesheet" />
```

If you’re using a preprocessor through something like [Harp](http://harpjs.com), you can import the files instead.

### With SCSS

```scss
@import "normalize";
@import "normalize-opentype";
```

## Contributing

Thanks for considering contributing! There’s information about how to [get started with normalize-opentype here](CONTRIBUTING.md).

If you’re new to all this GitHub, Open Source, JavaScript, Node.js, testing, wow all this stuff seems really difficult I just want to make my sites better stuff, I get it. I’m still there, too. Feel free to [send me an email](mailto:kenneth@chloi.io) or [open an issue here](http://github.com/kennethormandy/normalize-opentype.css/issues) and I’ll do my best to share some resources that have helped me out.

## Running locally

```bash
git clone https://github.com/kennethormandy/normalize-opentype.css
cd normalize-opentype.css
npm install
```

To compile your changes:

```bash
npm build
```

To view the tests:

```bash
npm test
```

## License

[The MIT License (MIT)](LICENSE.md)

Copyright © 2014 [Kenneth Ormandy](http://kennethormandy.com) & [Chloi Inc.](http://chloi.io)

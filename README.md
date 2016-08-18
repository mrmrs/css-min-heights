# css-min-heights 0.0.6

Css module of single purpose classes for min heights

#### Stats

213 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-min-heights
```

#### With Git

```
git clone https://github.com/tachyons-css/css-min-heights
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-min-heights";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-min-heights">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   MIN HEIGHTS
*/
.mn-hi-max { min-height: max-content; }
.mn-hi-min { min-height: min-content; }
.mn-hi-fit { min-height: fit-content; }
.mn-hi-fill { min-height: fill-available; }
@media screen and (min-width: 48em) {
 .mn-hi-max-ns { min-height: max-content; }
 .mn-hi-min-ns { min-height: min-content; }
 .mn-hi-fit-ns { min-height: fit-content; }
 .mn-hi-fill-ns { min-height: fill-available; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .mn-hi-max-m { min-height: max-content; }
 .mn-hi-min-m { min-height: min-content; }
 .mn-hi-fit-m { min-height: fit-content; }
 .mn-hi-fill-m { min-height: fill-available; }
}
@media screen and (min-width: 64em) {
 .mn-hi-max-l { min-height: max-content; }
 .mn-hi-min-l { min-height: min-content; }
 .mn-hi-fit-l { min-height: fit-content; }
 .mn-hi-fill-l { min-height: fill-available; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

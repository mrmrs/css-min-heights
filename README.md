# CSS MIN HEIGHTS

  Mobile-first classes for css-min-heights.
  Set the desired css-min-heights on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-min-heights
```
View on [npm](https://www.npmjs.org/package/css-min-heights)


## File Size

889B min-heights.css
722B min-heights.min.css 
188B minified and gzipped

## The Code
```
.mn-hi-max  { min-height: max-content; }
.mn-hi-min  { min-height: min-content; }
.mn-hi-fit  { min-height: fit-content; }
.mn-hi-fill { min-height: fill-available; }

@media screen and (min-width: 48em) {
  .mn-hi-max-ns  { min-height: max-content; }
  .mn-hi-min-ns  { min-height: min-content; }
  .mn-hi-fit-ns  { min-height: fit-content; }
  .mn-hi-fill-ns { min-height: fill-available; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {


  .mn-hi-max-m  { min-height: max-content; }
  .mn-hi-min-m  { min-height: min-content; }
  .mn-hi-fit-m  { min-height: fit-content; }
  .mn-hi-fill-m { min-height: fill-available; }
}

@media screen and (min-width: 64em)  {
  .mn-hi-max-l  { min-height: max-content; }
  .mn-hi-min-l  { min-height: min-content; }
  .mn-hi-fit-l  { min-height: fit-content; }
  .mn-hi-fill-l { min-height: fill-available; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


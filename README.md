# css-min-heights

Functional CSS for min-heights

## Filesize

| File | Size |
|------|------|
| `dist/min-heights.css` | 913 bytes |
| `dist/min-heights.min.css` | 683 bytes (170 Gzipped) |

## Install

```sh
npm install css-min-heights
```

## Usage

### Import

```css
@import "css-min-heights";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-min-heights/dist/min-heights.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-min-heights/dist/min-heights.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.mn-hi-max` | `min-height: max-content;` |
| `.mn-hi-min` | `min-height: min-content;` |
| `.mn-hi-fit` | `min-height: fit-content;` |
| `.mn-hi-fill` | `min-height: fill-available;` |
| `.mn-hi-max-s` | `min-height: max-content;` |
| `.mn-hi-min-s` | `min-height: min-content;` |
| `.mn-hi-fit-s` | `min-height: fit-content;` |
| `.mn-hi-fill-s` | `min-height: fill-available;` |
| `.mn-hi-max-m` | `min-height: max-content;` |
| `.mn-hi-min-m` | `min-height: min-content;` |
| `.mn-hi-fit-m` | `min-height: fit-content;` |
| `.mn-hi-fill-m` | `min-height: fill-available;` |
| `.mn-hi-max-l` | `min-height: max-content;` |
| `.mn-hi-min-l` | `min-height: min-content;` |
| `.mn-hi-fit-l` | `min-height: fit-content;` |
| `.mn-hi-fill-l` | `min-height: fill-available;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.mn-hi-max-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/min-heights.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/min-heights.css` — formatted
- `dist/min-heights.min.css` — minified

## License

MIT

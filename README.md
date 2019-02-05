# docsify-theme-nearform

## Usage

Import the docsify-themeable defaults and this theme.

```html
<link
  rel="stylesheet"
  href="//unpkg.com/docsify-themeable@0/dist/css/theme-defaults.css"
/>
<link
  rel="stylesheet"
  href="//unpkg.com/@nearform/docsify-theme-nearform/theme-nearform.min.css"
/>
```

## Contributing

We try to do all styling via the css variables that are exposed by docsify-themeable, their [documentation](https://jhildenbiddle.github.io/docsify-themeable/#/customization) lists the available options.

If it's not possible to do something with the vars then we write css, this should be kept to a minimum.

> Please use a version of `npm` version greater than 5.7.0 for `release` to work.

To publish a new release please run `npm run release`. You will be guided through selecting a version and it will automatically tag the commit etc.

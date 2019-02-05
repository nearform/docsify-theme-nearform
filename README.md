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
  href="//unpkg.com/@nearform/docsify-theme-nearform/theme-nearform.css"
/>
```

### Fonts

By default the font family will use system fonts. If you want to use the same font as the NearForm website (Archia Regular) you can copy the `fonts/` folder from this repo into your `docs/` folder and then add this css snippet in a style tag.

```html
<style>
  @font-face {
    font-family: 'archiaregular';
    src: url('fonts/archia-regular-webfont.eot');
    src: url('fonts/archia-regular-webfont.eot?#iefix') format('embedded-opentype'),
      url('fonts/archia-regular-webfont.woff2') format('woff2'),
      url('fonts/archia-regular-webfont.woff') format('woff'), url('fonts/archia-regular-webfont.ttf')
        format('truetype');
    font-weight: normal;
    font-style: normal;
  }
</style>
```

Alternatively you can use `Poppins` by importing that.

```html
<link
  href="https://fonts.googleapis.com/css?family=Poppins:100,300,400"
  rel="stylesheet"
/>
```

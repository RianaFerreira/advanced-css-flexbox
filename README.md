# Advanced CSS - flexbox
Advanced css exploring the use of flexbox to build a website

Browser support https://caniuse.com/#search=flex
Tutorial game http://flexboxfroggy.com/

### GETTING STARTED
Remember the package.json file is copied over without all the package library files.

**NOTE:** Customise the scripts as need for the build process.

Install the libraries
```
$ npm install
```

Start the development server
```
$ npm run start
```

### BASIC SETUP
* Simplified architecture
* CSS custom properties instead of SASS variables
  -> Don't need a preprocessor.
  -> Can be manipulated in JS and DevTools.
  -> Easier to use in the calc function.
  -> Cascade and are inherited.
* Layout with flex properties.

### IMAGES
* Scalable Vector Graphics (SVG) icons vs font icons.
* Find and generate SVGs icomoon.io
* Use SVG sprites in HTML.
* Change colour of SVG icon in CSS.
* Advanced flexbox alignment techniques:
  -> `justify-content`
  -> `align-items`
  -> `align-self`
  -> `flex`

### SIDE NAVIGATION EFFECTS
* Hover effect - `scaleY` with multiple transition properties
* `currentColor` CSS variable
* Advanced flexbox alignment technique - `flex-direction`

### MAIN CONTENT EFFECTS
* `infinite` animation property
* `margin: auto` with flexbox
* Advanced flexbox alignment technique - `flex-wrap`
* CSS masks - `mask-size` and `mask-image`

### RESPONSIVE MEDIA QUERIES
* Browser support for flex https://caniuse.com/#search=flex
* Feature @support query for mask in new browsers and fallback for older browsers

# reveal-template

## A git repo that has `reveal.js` set up

The point of this repo was to have a defined template for making `reveal.js` presentations somewhat systematically.

---

### Filestructure

The `css` folder contains two files: `reveal.css` and `presentation.css`. The former is stock and contains the bare minimum from `reveal.js`, and the latter contains customizations by me.

The `js` folder is for holding Javascript files, including `reveal.js`. Auxiliary scripts, such as `reveal.js-d3`, are included here as well.

The `images` folder is for containing static images, such as logos and whatnot.

The `data` folder will hold JSON for dynamic visualizations, made with stuff like `d3` and `vega-lite`.

---

## Credit/References

### CSS code

The CSS was generated using the "black" template from `reveal.js`.

### External Packages

#### Data Visualizations

For visualizations, I am using `reveal.js-d3.` which will allow for figures in the presentation to be animated with slide transitions.

https://github.com/gcalmettes/reveal.js-d3

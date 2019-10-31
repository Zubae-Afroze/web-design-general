# Important notes

## Beautiful Typography

* Font size - 15px to 25px
* Headline - H1 - 60px and H2 - 32 just a round value, no real limits
* As the font size improves, reduce font weight
* Line spacing - 125% - 150%
* 45 to 90 chars per line
* Choose good looking fonts

## Colors

* Use single base color
* Avoid Black
* Flat UI color is always good
* Always create a color palate
* Red - Power, Passion
* Orange - Cheerfulness
* Yellow - Happiness, Curiosity
* Green - Money, Harmony
* Blue - Peace, Trustworthiness, Stability
* Purple - Nobility, Luxury
* Pink - Romance, Affection

## Images

* Have text to image contrast
* Overlay the image with color to achieve contrast
* Overlay Color Gradients are good too
* Text in Opaque Box
* Blur the image
* Image Floor Fade

```CSS
/* Overlay the image */
.darken {
background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(YOUR IMAGE HERE);
}

/* Inside a Text Box */
.text-box {
background-color: rgba(0, 0, 0, 0.5);
color: #fff;
display: inline;
padding: 10px;
}

/*Floor Fade*/
.floor-fade {
background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.6) ), url(YOUR IMAGE HERE);
}
```

## Icons

* Icons to features, or steps to achieve some goal
* Always use SVG, Vector images
* Label Icons, to avoid confusion
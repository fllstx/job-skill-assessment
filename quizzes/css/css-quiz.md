## CSS

### What is the CSS selector for an `<a>` tag containing the title attribute?

- [x] `a[title]`
- [ ] `a > title`
- [ ] `a=title`
- [ ] `a.title`

### When adding transparency styles, what is the difference between using the opacity property versus the background property with an `rgba()` value?

- [ ] Opacity specifies the level of transparency of the child elements. Background with an `rgba()` value applies transparency to the background color only.
- [ ] Opacity applies transparency to the background color only. Background with an `rgba()` value specifies the level of transparency of an element, as a whole, including its content.
- [x] Opacity specifies the level of transparency of an element, including its content. Background with an `rgba()` value applies transparency to the background color only.
- [ ] Opacity applies transparency to the parent and child elements. Background with an `rgba()` value specifies the level of transparency of the parent element only.

### If the width of the container is 500 pixels, what would the width of the three columns be in this layout?

```css
.grid {
  display: grid;
  width: 500px;
  grid-template-columns: 50px 1fr 2fr;
}
```

- [x] 50px, 150px, 300px
- [ ] 50px, 200px, 300px
- [ ] 50px, 100px, 200px
- [ ] 50px, 50px, 100px

### In this example, according to cascading and specificity rules, what color will the link be?

```css
.example {
  color: yellow;
}
ul li a {
  color: blue;
}
ul a {
  color: green;
}
a {
  color: red;
}
```

```html
<ul>
  <li><a href="#" class="example">link</a></li>
  <li>list item</li>
  <li>list item</li>
</ul>
```

- [ ] green
- [x] yellow
- [ ] blue
- [ ] red

### In this example, what color will paragraphs one and two be?

```html
<section>
  <p>paragraph one</p>
</section>

<p>paragraph two</p>
```

```css
section p {
  color: red;
}
section + p {
  color: blue;
}
```

- [ ] Paragraph one will be blue, paragraph two will be red.
- [ ] Both paragraphs will be blue.
- [x] Paragraphs one will be red, paragraph two will be blue.
- [ ] Both paragraphs will be red.

### Which statement about the SVG image format is true?

- [ ] CSS can be applied to SVGs but JavaScript cannot be.
- [ ] SVGs work best for creating 3D graphics.
- [x] SVGs can be created as a vector graphic or coded using SVG specific elements such as &#x3C;svg&#x3E;, &#x3C;line&#x3E;, and &#x3C;ellipse&#x3E;.
- [ ] SVGs are a YAML-based markup language for creating vector graphics.

### When using position: fixed, what will the element always be positioned relative to?

- [ ] the closest element with position: relative
- [x] the viewport
- [ ] the parent element
- [ ] the wrapper element

### By default, a background image will repeat...

- [ ] ...only if the background-repeat property is set to repeat
- [ ] ...indefinitely, vertically, and horizontally
- [ ] ...indefinitely on the horizontal axis only
- [ ] ...once, on the x and y axis

### What is the rem unit based on?

- [ ] The rem unit is relative to the font-size of the p element.
- [ ] You have to set the value for the rem unit by writing a declaration such as rem { font-size: 1 Spx; }
- [ ] The rem unit is relative to the font-size of the containing (parent) element.
- [ ] The rem unit is relative to the font-size of the root element of the page.

### In the following media query example, what conditions are being targeted?

```css
@media (min-width: 1024px), screen and (orientation: landscape) { … }
```

- [x] The rule will apply to a device that has either a width of 1024px or wider, or is a screen device in landscape mode.
- [ ] The rule will apply to a device that has a width of 1024px or narrower and is a screen device in landscape mode.
- [ ] The rule will apply to a device that has a width of 1024px or wider and is a screen device in landscape mode.
- [ ] The rule will apply to a device that has a width of 1024px or narrower, or is a screen device in landscape mode.

### When using the Flexbox method, what property and value is used to display flex items in a column?

- [x] flex-flow: column; or flex-direction: column
- [ ] flex-flow: column;
- [ ] flex-column: auto;
- [ ] flex-direction: column;

### When using flexbox, the "justify-content" property can be used to distribute the space between the flex items along the main axis. Which value should be used to evenly distribute the flex items within the container shown below?

![quote](./images/rm-2.png)

- [x] justify-content: space-around;
- [ ] justify-content: center;
- [ ] justify-content: auto;
- [ ] justify-content: space-between;

### What is the difference between `display:none` and `visibility:hidden`?

- [ ] Both will hide the element on the page, but display:none has greater browser support. visibility:hidden is a new property and does not have the best browser support
- [ ] display:none hides the elements but maintains the space it previously occupied. visibility:hidden will hide the element from view and remove it from the normal flow of the document
- [x] display:none hides the element from view and removes it from the normal flow of the document. visibility:hidden will hide the element but maintains the space it previously occupied.
- [ ] There is no difference; both will hide the element on the page

### What selector and property would you use to scale an element to be 50% smaller on hover?

- [ ] element:hover {scale: 0.5;}
- [x] element:hover {transform: scale(0.5);}
- [ ] element:hover {scale: 50%;}
- [ ] element:hover {transform: scale(50%);}

### The values for the font-weight property can be keywords or numbers. For each numbered value below, what is the associated keyword?

```css
font-weight: 400;
font-weight: 700;
```

- [ ] bold; normal
- [x] normal; bold
- [ ] light; normal
- [ ] normal; bolder

### What is NOT a valid way of declaring a padding value of 10 pixels on the top and bottom, and 0 pixels on the left and right?

- [x] padding: 10px 10px 0px 0px;
- [ ] padding: 10px 0px;
- [ ] padding: 10px 0;
- [ ] padding: 10px 0px 10px 0px;

### The calc() CSS function is often used for calculating relative values. In the example below, what is the specified margin-left value?

```css
.example {
  margin-left: calc(5% + 5px);
}
```

- [x] The left margin value is equal to 5% of its parents element's width plus 5px
- [ ] The left margin value is equal to 5% of the viewport width plus 5px
- [ ] The left margin value is equal to 5% of the closest positioned element's width plus 5px
- [ ] The left margin value is equal to 5% of the selected element's width (.example) plus 5px

### What is an alternate way to define the following CSS rule?

```css
font-weight: bold;
```

- [ ] font-weight: 400;
- [ ] font-weight: medium;
- [x] font-weight: 700;
- [ ] font-weight: Black;

### Using the following HTML and CSS example, what will equivalent pixel value be for .em and .rem elements?

```css
html {
  font-size: 10px;
}
body {
  font-size: 2rem;
}
.rem {
  font-size: 1.5rem;
}
.em {
  font-size: 2em;
}
```

```html
<body>
  <p class="rem"></p>
  <p class="em"></p>
</body>
```

- [ ] The .rem will be equivalent to 25px; the .em value will be 20px.
- [ ] The .rem will be equivalent to 15px; the .em value will be 20px.
- [x] The .rem will be equivalent to 15px; the .em value will be 40px.
- [ ] The .rem will be equivalent to 20px; the .em value will be 40px.

### What is the correct selector for targeting all text inputs that are not disabled?

- [ ] `input[type="text"]:not([disabled]) {...}`
- [ ] `input[type="text"]:not("disabled") {...}`
- [ ] `input[type*="text"]:not([disabled="disabled"]) {...}`
- [ ] `input[type="text"]:not([type="disabled"]) {...}`

### Suppose you want to have a list of items (.item) displayed in a row and in reverse order using flexbox. What is the error in the CSS below?

```css
.container {
  display: flex;
}
.item {
  border: 1px solid red;
  flex-direction: row-reverse;
}
```

- [ ] The value for flex-direction should be reverse-row.
- [ ] The .container element should have a property of flex: display.
- [x] The flex-direction property should be declared in the container.
- [ ] The display value should be flex-inline to display the items in a row.

### There are currently four viewport-percentage lengths that can be used to define the value relative to the viewport size: vw, vh, vmin, and vmax. If the current viewport size has a width of 800px and a height of 600px, what will these values be equivalent to in pixels?

```css
10vw = ?px
10vh = ?px
10vmin = ?px
10vmax = ?px
```

- [x] 10vw = 80px
      10vh = 60px
      10vmin = 60px
      10vmax = 80px

- [ ] 10vw = 60px
      10vh = 80px
      10vmin = 80px
      10vmax = 60px

- [ ] 10vw = 8px
      10vh = 6px
      10vmin = 6px
      10vmax = 8px

- [ ] 10vw = 6px
      10vh = 8px
      10vmin = 8px
      10vmax = 6px

### To make the font size of an element one size smaller than the font size of the element's container, which style property would you apply?

- [ ] `font-size: reduce;`
- [ ] `font-size: 8px;`
- [ ] `font-size: -1em;`
- [x] `font-size: smaller;`

### Which style rule would you apply to set the background image to display the contents of the wood.png file?

- [ ] `background-image: file('wood.png');`
- [x] `background-image: url('wood.png');`
- [ ] `background-image: wood.png;`
- [ ] `image: wood.png`

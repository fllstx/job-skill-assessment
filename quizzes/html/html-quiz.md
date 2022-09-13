## HTML

### What is the best way to apply bold styling to text?

- [ ] `<strong>`
- [ ] Use CSS.
- [ ] `<bold>`
- [ ] `<b>`

### When is the `<link>` tag used?

- [ ] when linking style sheets, JavaScript, and icons for mobile apps
- [ ] when linking style sheets, favicons, and preloading assets
- [ ] when linking one webpage to another
- [ ] when linking style sheets, external URLs, and favicons

### When should you use the `<aside>` element?

- [ ] when the content can be removed without detracting from the page's message
- [ ] for anything you want to move to the side, like a pull quote box, a sidebar, or an image with text wrapping around it
- [ ] for anything in parentheses
- [ ] for anything in a sidebar

### What is the best way to code the sample shown?

![Sample text](images/ss-2.png?raw=true)

- [ ] A

```html
<details>
  <summary>Parmesan Deviled Eggs</summary>
  <p>
    These delectable little bites are made with organic eggs, fresh Parmesan, and chopped pine nuts.
  </p>
</details>
```

- [ ] B

```html
<h4>▸ Parmesan Deviled Eggs</h4>
<p>
  These delectable little bites are made with organic eggs, fresh Parmesan, and chopped pine nuts.
</p>
```

- [ ] C

```html
<details open>
  <summary>Parmesan Deviled Eggs</summary>
  <p>
    These delectable little bites are made with organic eggs, fresh Parmesan, and chopped pine nuts.
  </p>
</details>
```

- [ ] D

```html
<details>
  <h4>▸ Parmesan Deviled Eggs</h4>
  <p>
    These delectable little bites are made with organic eggs, fresh Parmesan, and chopped pine nuts.
  </p>
</details>
```

### When should you use `<ol>` and `<ul>` elements?

- [ ] Use `<ul>` when you want a bulleted list and `<ol>` when you want a numbered list.
- [ ] Use `<ul>` when you have a list of items in which the order of the items matters. Use `<ol>` when you have a list of items that could go in any order.
- [ ] Use `<ol>` when you want a bulleted list and `<ul>` when you want a numbered list.
- [ ] Use `<ol>` when you have a list of items in which the order of the items matters. Use `<ul>` when you have a list of items that could go in any order.

### What is the difference between the `<div>` and `<span>` tags?

- [ ] `<div>` is used where a generic block-level tag is needed, while `<span>` is used where a generic inline tag is needed.
- [ ] `<div>` is used for major divisions on a page, while `<span>` is used to span across columns.
- [ ] `<div>` is the industry-standard default tag, but you could use `<span>` if you prefer.
- [ ] `<div>` is used where a generic inline tag is needed, while `<span>` is used where a generic block-level tag is needed.

### What is the correct markup for `alt` attribute of an image?

- [ ] A

```html
<img src="cubism.jpg" alt="Version of ""Whistler's Mother"" in cubist style">
```

- [ ] B

```html
<img src="cubism.jpg" alt="Version of "Whistler's Mother" in cubist style">
```

- [ ] C

```html
<img src="cubism.jpg" alt='Version of "Whistler\'s Mother" in cubist style'>
```

- [ ] D

```html
<img src="cubism.jpg" alt="Version of \"Whistler's Mother\" in cubist style">
```

### What is the best semantic markup for the sentence shown?

```
On July 21, 1969, Neil Armstrong said, "One small step for man, one giant leap for mankind."
```

- [ ] A

```html
<p>
  On <time datetime="1969-07-21">July 21, 1969</time>, Neil Armstrong said,
  <q cite="https://www.hq.nasa.gov/alsj/a11l/a11.html"
    >One small step for man, one giant leap for mankind.</q
  >
</p>
```

- [ ] B

```html
<p>
  On July 21, 1969, Neil Armstrong said,
  <q cite="https://www.hq.nasa.gov/alsj/a11l/a11.html"
    >"One small step for man, one giant leap for mankind."</q
  >
</p>
```

- [ ] C

```html
<p>
  On July 21, 1969, Neil Armstrong said,
  <q>"One small step for man, one giant leap for mankind."</q>
</p>
```

- [ ] D

```html
<p>
  On <time datetime="07-21-1969">July 21, 1969</time>, Neil Armstrong said,
  <q cite="https://www.hq.nasa.gov/alsj/a11l/a11.html"
    >One small step for man, one giant leap for mankind.</q
  >
</p>
```

### What does the code shown below accomplish?

```html
<picture>
  <source srcset="image1.jpg" media="(min-width: 1000px)" />
  <source srcset="image2.jpg" media="(min-width: 750px)" />
  <img src="image3.jpg" />
</picture>
```

- [ ] It displays image1.jpg at 1000px and higher, image2.jpg at 750-999px, and image3.jpg at 749px and lower.
- [ ] It displays image1.jps at 1000px and higher and image2.jpg at 750-999px, image3.jpg is a default in case `<picture>` is not supported.
- [ ] It displays image1.jpg at 1000px and higher and image2.jpg at 750px and higher, image3.jpg is a default in case `<picture>` is not supported.
- [ ] It displays image1.jpg, image2.jpg and image3.jpg at 1000px and higher.

### What does the `<label>` element do?

- [ ] It labels webpages with important information.
- [ ] It creates an ID for a corresponding input element.
- [ ] It overrides the name attribute's value on a child input element.
- [ ] It programmatically associates a text label with an interface element.

### To get a link to open in a new window or tab, use the **\_** attribute

- [ ] `_blank`
- [ ] `_self`
- [ ] `_new`
- [ ] `_parent`

### What is the correctly nested markup for this list?

![Sample list](images/ss-6.png?raw=true)

- [ ] A

```html
<ul>
  <li>
    office
    <ol style="circle">
      <li>staple</li>
      <li>paper</li>
    </ol>
  </li>
  <li>
    groceries
    <ol style="circle">
      <li>milk</li>
    </ol>
  </li>
</ul>
```

- [ ] B

```html
<ul>
  <li>
    Office Supplies
    <ul>
      <li>Stapler</li>
      <li>Paper clips</li>
    </ul>
  </li>
  <li>
    Groceries
    <ul>
      <li>Milk</li>
    </ul>
  </li>
</ul>
```

- [ ] C

```html
<ul>
  <li>office</li>
  <li>staple</li>
  <li>paper</li>
  <li>groceries</li>
  <li>milk</li>
</ul>
```

### What should fill the blank below?

```html
<link href="print.css" rel="stylesheet" _____="print" />
```

- [ ] title
- [ ] type
- [ ] device
- [ ] media

### Which code snippet creates the layout shown, starting at `<table>` and ending at `</table>`?

![Table](images/ss-1.png?raw=true 'table')

- [ ] A

```html
<tr>
  <td>Table cell 1</td>
  <td>Table cell 2</td>
</tr>
<tr>
  <td rowspan="2">Table cell 3</td>
</tr>
```

- [ ] B

```html
<tr>
  <td>Table cell 1</td>
  <td>Table cell 2</td>
  <td>Table cell 3</td>
</tr>
```

- [ ] C

```html
<tr>
  <td>Table cell 1</td>
  <td>Table cell 2</td>
</tr>
<tr>
  <td colspan="2">Table cell 3</td>
</tr>
```

- [ ] D

```html
<tr>
  <td>Table cell 1</td>
  <td>Table cell 2</td>
</tr>
<tr>
  <td>Table cell 3</td>
</tr>
```

### What is the primary purpose of the `<canvas>` tag?

- [ ] It allows raster images to be rendered on the webpage.
- [ ] It displays annotated images.
- [ ] It allows drawing on a bitmap via JavaScript.
- [ ] It allows vector images to be rendered on the webpage.

### What is the correct way to include a stylesheet named **style.css** in the `<head>` of your document?

- [ ] `<style link="style.css">`
- [ ] `<link rel="stylesheet" href="style.css">`
- [ ] `<style src="style.css"></style>`
- [ ] `<link style="style.css">`

### What is the correct way to code a comment in HTML?

- [ ] `//this is a comment`
- [ ] `/* this is a comment */`
- [ ] `<! this is a comment ->`
- [ ] `<!-- this is a comment -->`

### What is the purpose of async in this code?

`<script async src="myscript.js"></script>`

- [ ] It downloads the script from the server when resources allow.
- [ ] It runs the script after HTML parsing is complete.
- [ ] It runs the script when the script is ready.
- [ ] It pauses the parsing of HTML code while the script runs.

### In this code, what is the purpose of defer?

`<script defer src="myscript.js"></script>`

- [ ] It downloads the script from the server when resources allow.
- [ ] It runs the script after HTML parsing is complete.
- [ ] It runs the script when the script is ready.
- [ ] It pauses the parsing of HTML code while the script runs.

### What is the difference between the `<head>` and `<header>` tags?

- [ ] There is only one `<head>` tag per page, while there may be many `<header>` tags.
- [ ] The `<head>` tag may contain CSS and Javascript links, while the `<header>` tag may contain headings and navigational links.
- [ ] all of these answers
- [ ] The `<head>` tag contains meta information, while the `<header>` tag contains navigation, logos, and other page identifying content.

### When should you use the `<article>` element?

- [ ] For blog posts and other social media items
- [ ] For the main content area of your website
- [ ] When the content stands alone as a unit, is suitable for syndication, or is reusable
- [ ] To associate comments with a blog post

### What is the purpose of the `class` attribute?

- [ ] Classes allow CSS to select specific elements on the page. You may list as many class names within the class attribute as you wish, separated by spaces.
- [ ] Classes allow CSS and JavaScript to select specific elements on the page. You may list only one class name per class attribute.
- [ ] Classes allow CSS to select specific elements on the page. You may list only one class name per class attribute.
- [ ] Classes allow CSS and JavaScript to select specific elements on the page. You may list as many class names within the class attribute as you wish, separated by spaces.

### Which choice is not a legal type attribute for the `<input>` tag?

- [ ] `<input type="color">`
- [ ] `<input type="tel">`
- [ ] `<input type="week">`
- [ ] `<input type="num">`

### What is the most semantically accurate way to make up a main navigation bar, displayed in a horizontal direction?

- [ ] A

```html
<p>
  <a href="index.html">Home</a>
  <a href="about.html">About</a>
  <a href="contact.html">Contact</a>
</p>
```

- [ ] B

```html
<nav>
  <a href="index.html">Home</a>
  <a href="about.html">About</a>
  <a href="contact.html">Contact</a>
</nav>
```

- [ ] C

```html
<nav>
  <ol>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="contact.html">Contact</a></li>
  </ol>
</nav>
```

- [ ] D

```html
<nav>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="contact.html">Contact</a></li>
  </ul>
</nav>
```

### For the HTML code below, when will "Sample Text" display to the browser?

```html
<noscript>Sample Text</noscript>
```

- [ ] when there is no JavaScript used on this webpage
- [ ] when JavaScript is not supported by the browser or if JavaScript is disabled in the browser
- [ ] when JavaScript is disabled in the web browser
- [ ] when JavaScript is not supported by the web browser

### What is the difference between the `<svg>` and `<canvas>`?

- [ ] `<svg>` produces vector graphics, while `<canvas>` produces raster graphics.
- [ ] `<svg>` integrates with JavaScript, while `<canvas>` does not.
- [ ] `<svg>` produces raster graphics, while `<canvas>` produces vector graphics.
- [ ] `<svg>` cannot be used as a background image, while `<canvas>` can be used as a background

### What is the difference between the _readonly_ and _disabled_ attributes for the `<textarea>` element?

- [ ] _readonly_ allows clicking in the `<textarea>` element. _disabled_ prevents all interaction with the control.
- [ ] _readonly_ is invalid attribute for `<textarea>`, while _disabled_ is a valid attribute.
- [ ] _disabled_ allows clicking in the `<textarea>` element. _readonly_ prevents all interaction with the control.
- [ ] _disabled_ is invalid attribute for `<textarea>`, while _readonly_ is a valid attribute.

### In this code, what is _target_?

`<a target="_blank">...</a>`

- [ ] an attribute
- [ ] a tag
- [ ] content
- [ ] an element

### Which choice is the most semantically correct markup for specifying the first definition of a term?

- [ ] `<p>`The `<dl>`focal length`</dl>` of a lens gives the distance from the lens to the image sensor.`</p>`
- [ ] `<p>`The `<dfn>`focal length`<dfn>` of a lens gives the distance from the lens to the image sensor.`</p>`
- [ ] `<p>`The `<dt>`focal length`</dt>` of a lens gives the distance from the lens to the image sensor.`</p>`
- [ ] `<p>`The `<dd>`focal length`</dd>` of a lens gives the distance from the lens to the image sensor.`</p>`

### How would you mark up a piece of ASCII art (an emoticon) in an accessible way?

- [ ] `<pre role="emoticon" aria-label="ASCII emoticon of a shrug">¯\_(ツ)_/¯</pre>`
- [ ] `<pre role="img" aria-label="ASCII emoticon of a shrug">¯\_(ツ)_/¯</pre>`
- [ ] `<dfn title="ASCII emoticon of a shrug">¯\_(ツ)_/¯</dfn>`
- [ ] `<label for="art">ASCII emoticon of a shrug</label><pre role="img" id="art">¯\_(ツ)_/¯</pre>`

### Which example is a standard way in HTML5 for adding author metadata to a page?

- [ ] `<metadata name="author" content="Author Name">`
- [ ] `<meta name="author">Author Name</meta>`
- [ ] `<meta name="creator" content="Author Name">`
- [ ] `<meta name="author" content="Author Name">`

### Given the following requirements, select the correct `input` configuration: An `input` that allows the user to select from a range of integer values between 0 and 100 (inclusive) in increments of 5.

- [ ] `<input type="range" min="0" max="100" by="5" />`
- [ ] `<input type="range" min="0" max="100" step="5" />`
- [ ] `<input type="number" min="0" max="100" step="5" />`
- [ ] `<input type="number" min="0" max="100" by="5" />`

### Which choice is valid markup for a `<head>` element?

- [ ] `<head class="Page Section Information" id="head"><title>Page Title</title></head>`
- [ ] `<head><title>Page Title</title> <img src="favicon.icon" alt=""></head>`
- [ ] `<head><title>Page Title</title> <data value="email">email@example.com</data></head>`
- [ ] `<head><title>Page Title</title><address>email@example.com</address></head>`

### Which description is coded correctly?

- [ ] A

```html
<dl>
  <dt>Server</dt>
  <dd>Software used to serve webpages, like Apache.</dd>
  <dd>Hardware used to provide data to other computers.</dd>
  <!-- Other terms and descriptions -->
</dl>
```

- [ ] B

```html
<dt>
  <dl>Server</dl>
  <dd>Software used to serve webpages, like Apache.</dd>
  <dd> Hardware used to provide data to other computers.</dd>
  <!-- Other terms and descriptions -->
</dt>
```

- [ ] C

```html
<dl>
  <dt>Server</dt>
  <dd>Software used to serve webpages, like Apache.</dd>
  <dt>Hardware used to provide data to other computers.</dt>
  <!-- Other terms and descriptions -->
</dl>
```

- [ ] D

```html
<dl>
  <dd>Server</dd>
  <dt>Software used to serve webpages, like Apache.</dt>
  <dt>Hardware used to provide data to other computers.</dt>
  <!-- Other terms and descriptions -->
</dl>
```

### What is wrong with this code?

```html
<ul>
  <h2>Espresso Drinks</h2>
  <li>Espresso</li>
  <li>Latte</li>
  <li>Cappuccino</li>
  <li>Mocha</li>
</ul>
```

- [ ] Nothing is wrong.
- [ ] `<ul>` cannot contain a heading element as a direct child.
- [ ] An `<h1>` should be used here instead of an `<h2>` tag.
- [ ] Only `<ol>` allows direct descendants to contain elements other than an `<li>`, so use an `<ol>` here instead.

### A designer gave you CSS code that should run only when the device rendering the page is in dark mode. How would you embed that code?

- [ ] `<style media="light-mode: false">/* CSS code */</style>`
- [ ] `<style media="color-mode: dark">/* CSS code */</style>`
- [ ] `<style media="prefers-color-scheme: dark">/* CSS code */</style>`
- [ ] `<style media="color-scheme: dark">/* CSS code */</style>`

### How would you mark up a header for a table row?

- [ ] A

```html
<table>
  <thead scope="row">
    <th row="1">Header</th>
  </thead>
  <tr>
    <td>10</td>
    <td>18</td>
  </tr>
</table>
```

- [ ] B

```html
<table>
  <tr>
    <th scope="row">Header</th>
    <td>10</td>
    <td>18</td>
  </tr>
</table>
```

- [ ] C

```html
<table>
  <tr>
    <thead scope="row">
      Header
    </thead>
    <td>10</td>
    <td>18</td>
  </tr>
</table>
```

- [ ] D

```html
<table>
  <tr>
    <th>Header</th>
    <td>10</td>
    <td>18</td>
  </tr>
</table>
```

### Which statement is correct?

- [ ] The `<main>` element represents the dominant content of an `<article>` in a document.
- [ ] The `<main>` element represents the dominant content of a `<section>` of a document. You may have one `<main>` element per section.
- [ ] The `<main>` element represents the dominant content of your document. There can be only one `<main>` element that is not hidden.
- [ ] The `<article>` element represents the dominant content of your document. There can be only one `<article>` element that is not hidden.

## CSS Text

CSS has lot of properties for text formatting

#### Text Color

The `color` property is used to set the color of the text. The color is specified by:

- a color name - like "red"
- a HEX value - like "#ff0000"
- an RGB value - like "rgb(255,0,0)"

Look at [CSS Color Values](https://www.w3schools.com/cssref/css_colors_legal.asp) for a complete list of possible color values.

The default text color for a page is defined in the body selector.

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {
  color: blue;
}

h1 {
  color: green;
}
</style>
</head>
<body>

<h1>This is heading 1</h1>
<p>This is an ordinary paragraph. Notice that this text is blue. The default text color for a page is defined in the body selector.</p>
<p>Another paragraph.</p>

</body>
</html>

```



#### Text Color and Background Color

Here we will see how we can format color and background of text and element.

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: lightgrey;
  color: blue;
}

h1 {
  background-color: black;
  color: white;
}
</style>
</head>
<body>

<h1>This Heading is Black with White Text</h1>
<p>This page has a grey background color and a blue text.</p>
<p>Another paragraph.</p>

</body>
</html>
```



#### Text Alignment

The `text-align` property is used to set the horizontal alignment of a text. A text can be left or right aligned, centered, or justified.

The following example shows center aligned, and left and right aligned text (left alignment is default if text direction is left-to-right, and right alignment is default if text direction is right-to-left):

```
<!DOCTYPE html>
<html>
<head>
<style>
h3 {
  text-align: center;
}

h4 {
  text-align: left;
}

h5 {
  text-align: right;
}
</style>
</head>
<body>

<h3>Heading 1 (center)</h3>
<h4>Heading 2 (left)</h4>
<h5>Heading 3 (right)</h5>

<p>The three headings above are aligned center, left and right.</p>

</body>
</html>

```

###### Text Justify

When the `text-align` property is set to "justify", each line is stretched so that every line has equal width, and the left and right margins are straight (like in magazines and newspapers):

```css
div {
  text-align: justify;
}
```

#### Text Direction

The `direction` and `unicode-bidi` properties can be used to change the text direction of an element:

```html
<!DOCTYPE html>
<html>
<head>
<style>
p.ex1 {
  direction: rtl;
  unicode-bidi: bidi-override;
}
</style>
</head>
<body>

<p>This is the default text direction.</p>

<p class="ex1">This is right-to-left text direction.</p>

</body>
</html>

```

#### Vertical Alignment

The `vertical-align` property sets the vertical alignment of an element.

```html
<!DOCTYPE html>
<html>
<head>
<style>
img.a {
  vertical-align: baseline;
}

img.b {
  vertical-align: text-top;
}

img.c {
  vertical-align: text-bottom;
}

img.d {
  vertical-align: sub;
}

img.e {
  vertical-align: super;
}
</style>
</head>
<body>

<h1>The vertical-align Property</h1>

<h2>vertical-align: baseline (default):</h2>
<p>An <img class="a" src="purplebox.gif" width="9" height="9"> image with a default alignment.</p> 

<h2>vertical-align: text-top:</h2>
<p>An <img class="b" src="purplebox.gif" width="9" height="9"> image with a text-top alignment.</p> 

<h2>vertical-align: text-bottom:</h2>
<p>An <img class="c" src="purplebox.gif" width="9" height="9"> image with a text-bottom alignment.</p>

<h2>vertical-align: sub:</h2>
<p>An <img class="d" src="purplebox.gif" width="9" height="9"> image with a sub alignment.</p> 

<h2>vertical-align: sup:</h2>
<p>An <img class="e" src="purplebox.gif" width="9" height="9"> image with a super alignment.</p>

</body>
</html>

```

#### Text Decoration

The `text-decoration` property is used to set or remove decorations from text. The value `text-decoration: none;` is often used to remove underlines from links:

```css
a {
  text-decoration: none;
}
```

Other text line decoration used to overline ,underline and line-through etc

```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  text-decoration: overline;
}

h2 {
  text-decoration: line-through;
}

h3 {
  text-decoration: underline;
}
</style>
</head>
<body>

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>

</body>
</html>

```


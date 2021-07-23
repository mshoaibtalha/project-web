

## CSS Background

With css background property we can change background of the body or element.

```css
body {
  background-color: blue;
}
```

Also we can change background color of element.

```html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  background-color: green;
}

div {
  background-color: lightblue;
}

p {
  background-color: yellow;
}
</style>
</head>
<body>

<h1>CSS background-color example!</h1>
<div>
This is a text inside a div element.
<p>This paragraph has its own background color.</p>
We are still in the div element.
</div>

</body>
</html>

```



#### Opacity / Transparency

The `opacity` property specifies the opacity/transparency of an element. It can take a value from 0.0 - 1.0. The lower value, the more transparent:

```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  background-color: green;
}

div.first {
  opacity: 0.1;
}

div.second {
  opacity: 0.3;
}

div.third {
  opacity: 0.6;
}
</style>
</head>
<body>

<h1>Transparent Box</h1>
<p>When using the opacity property to add transparency to the background of an element, all of its child elements become transparent as well. This can make the text inside a fully transparent element hard to read:</p>

<div class="first">
  <h1>opacity 0.1</h1>
</div>

<div class="second">
  <h1>opacity 0.3</h1>
</div>

<div class="third">
  <h1>opacity 0.6</h1>
</div>

<div>
  <h1>opacity 1 (default)</h1>
</div>

</body>
</html>
```



####  CSS Background Image

The `background-image` property specifies an image to use as the background of an element.

```css
body {
  background-image: url("house.png");
}
```

###### CSS Background no-repeat:

```css
body {
  background-image: url("house.png");
  background-repeat: no-repeat;
}
```

###### CSS background Attachment:

The `background-attachment` property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page):

```css
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;
}
```



source:www.w3.org , www.w3school.com
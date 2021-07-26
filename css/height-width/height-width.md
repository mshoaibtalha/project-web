### CSS Height and Width

The CSS `height` and `width` properties are used to set the height and width of an element. The height and width properties do not include padding, borders, or margins. It sets the height/width of the area inside the padding, border, and margin of the element.

```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  height: 50px;
  width: 100%;
  border: 1px solid blue;
}
</style>
</head>
<body>

<h2>CSS height and width </h2>

<div>This element has a height of 50 pixels and a width of 100%.</div>

</body>
</html>
```

#### CSS Height and Width Values

- `auto` - This is default. The browser calculates the height and width
- `length` - Defines the height/width in px, cm etc.
- `%` - Defines the height/width in percent of the containing block
- `initial` - Sets the height/width to its default value
- `inherit` - The height/width will be inherited from its parent value

```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  height: 100px;
  width: 500px;
  background-color: powderblue;
}
</style>
</head>
<body>

<h2>Set the height and width of an element</h2>

<div>This div element has a height of 100px and a width of 500px.</div>

</body>
</html>
```



#### Setting max-width

```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  max-width: 500px;
  height: 100px;
  background-color: powderblue;
}
</style>
</head>
<body>

<h2>Set the max-width of an element</h2>

<div>This div element has a height of 100px and a max-width of 500px.</div>

<p>Resize the browser window to see the effect.</p>

</body>
</html>
```



##### Height-Width Properties

| [height](https://www.w3schools.com/cssref/pr_dim_height.asp) | Sets the height of an element         |
| ------------------------------------------------------------ | ------------------------------------- |
| [max-height](https://www.w3schools.com/cssref/pr_dim_max-height.asp) | Sets the maximum height of an element |
| [max-width](https://www.w3schools.com/cssref/pr_dim_max-width.asp) | Sets the maximum width of an element  |
| [min-height](https://www.w3schools.com/cssref/pr_dim_min-height.asp) | Sets the minimum height of an element |
| [min-width](https://www.w3schools.com/cssref/pr_dim_min-width.asp) | Sets the minimum width of an element  |
| [width](https://www.w3schools.com/cssref/pr_dim_width.asp)   | Sets the width of an element          |
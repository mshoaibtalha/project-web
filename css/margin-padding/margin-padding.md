### CSS Margin

WIth CSS margin we can create space around Element outside of specified boarder.

Margin can be top,bottom,left and right

```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  margin: 70px;
  border: 1px solid black;
}
</style>
</head>
<body>

<h2>CSS Margins</h2>
<div>This element has a margin of 70px.</div>

</body>
</html>
```

We can give a general margin which applies to all sides or we can specified margin on each side

- `margin-top`
- `margin-right`
- ``margin-bottom``
- ``margin-left`

All the margin properties can have the following values:

- auto - the browser calculates the margin
- *length* - specifies a margin in px, pt, cm, etc.
- *%* - specifies a margin in % of the width of the containing element
- inherit - specifies that the margin should be inherited from the parent element.



```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  border: 1px solid black;
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
  background-color: lightblue;
}
</style>
</head>
<body>

<h2>Using individual margin properties</h2>

<div>This div element has a top margin of 100px, a right margin of 150px, a bottom margin of 100px, and a left margin of 80px.</div>

</body>
</html>
```

#### The Auto value

``margin=auto`` property automatically calculate margin from all side .You can set the margin property to `auto` to horizontally center the element within its container. The element will then take up the specified width, and the remaining space will be split equally between the left and right margins.
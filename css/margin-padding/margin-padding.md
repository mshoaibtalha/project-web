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



### CSS Padding

WIth CSS padding property we can create space in Element inside of specified boarder.

Padding can be top,bottom,left and right.



```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  padding: 80px;
  border: 1px solid red;
}
</style>
</head>
<body>

<h2>CSS Padding</h2>
<div>This element has a padding of 80px.</div>

</body>
</html>
```

We can give a general padding which applies to all sides or we can specified padding on each side

- `padding-top`
- `padding-right`
- ``padding-bottom``
- ``padding-left`

All the padding properties can have the following values:

- auto - the browser calculates the padding
- *length* - specifies a padding in px, pt, cm, etc.
- *%* - specifies a padding in % of the width of the containing element
- inherit - specifies that the padding should be inherited from the parent element.

```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  border: 1px solid black;
  background-color: lightblue;
  padding-top: 80px;
  padding-right: 40px;
  padding-bottom: 30px;
  padding-left: 80px;
}
</style>
</head>
<body>

<h2>Using individual padding properties</h2>

<div>This div element has a top padding of 80px, a right padding of 40px, a bottom padding of 30px, and a left padding of 80px.</div>

</body>
</html>
```



source: www.w3.org , www.w3school.com


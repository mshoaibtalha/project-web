### CSS Link 

We can style link in many ways with CSS. We can color,font backgroung and many things with css properties.

The four links states are:

- `a:link` - a normal, unvisited link
- `a:visited` - a link the user has visited
- `a:hover` - a link when the user mouses over it
- `a:active` - a link the moment it is clicked

###### Text Decoration

The `text-decoration` property is mostly used to remove underlines from links



```html
<!DOCTYPE html>
<html>
<head>
<style>
/* unvisited link */
a:link {
  color: red;
  text-decoration: none;
   background-color: yellow;
  }

/* visited link */
a:visited {
  color: green;
   background-color: cyan;
}

/* mouse over link */
a:hover {
  color: hotpink;
  text-decoration:underline;
  background-color: lightgreen;
}

/* selected link */
a:active {
 color: blue;
 text-decoration:underline;
  background-color: hotpink;
    
}
</style>
</head>
<body>

<h2>CSS Links</h2>
<p><b><a href="default.asp" target="_blank">This is a link</a></b></p>
<p><b>Note:</b> a:hover MUST come after a:link and a:visited in the CSS definition in order to be effective.</p>
<p><b>Note:</b> a:active MUST come after a:hover in the CSS definition in order to be effective.</p>

</body>
</html>
```


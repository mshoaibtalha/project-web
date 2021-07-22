#### What is CSS?

CSS stands for Cascading Style Sheets

CSS is the language we use to style an HTML document.

CSS describes how HTML elements should be displayed.

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
</style>
</head>
<body>

<h1>My First CSS Example</h1>
<p>This is a paragraph.</p>

</body>
</html>

```

#### Problem before CSS

HTML was NEVER intended to contain tags for formatting a web page!

HTML was created to describe the content of a web page, like:

<h1>This is a heading</h1>

<p>This is a paragraph.</p>

When tags like <font>, and color attributes were added to the HTML 3.2 specification, it started a nightmare for web developers. Development of large websites, where fonts and color information were added to every single page, became a long and expensive process.

To solve this problem, the World Wide Web Consortium (W3C) created CSS.

CSS removed the style formatting from the HTML page!'

#### How to insert CSS

- External CSS
- Internal CSS
- Inline CSS

We can write CSS internally in HTML inline in HTML tag or in `<head>` tag within `<style>`.

We can also make an external files of format .css and put link of style in `<head>` tag.

The style definitions are normally saved in external .css files.

With an external stylesheet file, you can change the look of an entire website by changing just one file.

#### CSS Syntax

#### ![](C:\Repos\project-web\html\images\selector.gif) 

CSS syntax has many components

- Selector
- Declaration

##### Element Selector

The element selector selects HTML elements based on the element name.

```css
<html>
<head>
<style>
p {
  text-align: center;
  color: red;
} 
</style>
</head>
<body>

<p>Hello World!.</p>
<p id="hellow">Hello London!</p>
<p>Hello Paris!</p>

</body>
</html>

```



##### ID Selector

HTML Element  can also by styled by id selector . Id must cotains #. 

```html
<!DOCTYPE html>
<html>
<head>
<style>
#hellow {
  text-align: center;
  color: orange;
}
</style>
</head>
<body>

<p id="hellow">Hello World!</p>
</body>
</html>
```



##### Class Selector

HTML element can be selected by class selector. It declared in class with understandable name allocation. It is declared as .class .

```html
<!DOCTYPE html>
<html>
<head>
<style>
.hellow {
  text-align: center;
  color: orange;
}
</style>
</head>
<body>

<p class="hellow">Hello World!</p>
</body>
</html>
```

source: www.w3school.com,www.w3.org 
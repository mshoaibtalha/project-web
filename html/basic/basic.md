# HTML introduction

I am writing these notes for my personal usages and as notes so if i forgot something i can check these notes .

HTML is basic building block of any web apllication.HTML stands for Hyper Text Mark up Language.HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

#### How HTML document starts

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```

- `<!DOCTYPE html>` tells that this document is an HTML5 document

- `<html>` element is the root element of page

- `<head>` element contains meta information about the HTML page

- `<title>` in title element we can define Title of page.
  fd
- `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

- `<h1>` element defines a large heading

- `<p>` element defines a paragraph

  #### HTML Element

  HTML element is everything from its starting tag to ending tag.

  <tagname>Content goes here...</tagname>

```html
<h1>My First Heading</h1>
<h2>My Scond Heading</h2>
<h3>My Thrid Heading</h3>
That goes til h6
<p>My first paragraph.</p>
```

#### HTML Attributes

##### The href Attribute

The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:

```html
<a href="https://wwww.google.com">Search Everything Goorle</a>
```

##### The src Attribute

The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

```html
<img src="house.jpg" />
```

## Class & ID Attributes of HTML

### Class Attribute

Class attributes defines the class of that particular HTML element.

Then we can use that class in CSS, JavaScript or in other language to style  or modify the content.

``` html
<style>
      .city {
        background-color: rgb(36, 179, 184);
        color: white;
        border: 2px solid black;
        margin: 20px;
        padding: 20px;
      }
    </style>
<div class="city">
      <h2>Oslo</h2>
      <p>Oslo is the capital of Norway.</p>
    </div>

    <div class="city">
      <h2>Amsterdam</h2>
      <p>Amsterdam is the capital of Netherland.</p>
    </div>

    <div class="city">
      <h2>Stockholm</h2>
      <p>Stockholm is the capital of Sweden.</p>
    </div>
```

We can write properties of Class in <style>{}<style/> tag and in within curly braces.

###### Same Class can belong to multiple HTML Elements as written in above example :

```html
<div class="city"> Oslo<div/>
<div class="city"> Amsterdam<div/>
<div class="city"> Stockholm<div/>
```

HTML elements can use more than one class

```html
<div class="city mainCity"> Oslo<div/>
```

This element has two classes one is CITY an other in mainCity

#### we can use Class to manipulate JavaScript: 

```html
<style>
      .city {
        background-color: rgb(36, 179, 184);
        color: white;
        border: 2px solid black;
        margin: 20px;
        padding: 20px;
      }
    </style>
<div class="city">
      <h2>Oslo</h2>
      <p>Oslo is the capital of Norway.</p>
    </div>

    <div class="city">
      <h2>Amsterdam</h2>
      <p>Amsterdam is the capital of Netherland.</p>
    </div>

    <div class="city">
      <h2>Stockholm</h2>
      <p>Stockholm is the capital of Sweden.</p>
    </div>
<p>Click the button to hide all elements with class name "city":</p>

<button onclick="myFunction()">Hide elements</button>
<script>
function myFunction() {
  var x = document.getElementsByClassName("city");
  for (var i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
}
</script>
```

### ID Attribute:

Id attribute defines the id of a HTML element. The id attribute specifies a unique id for an HTML element. Unlike Class ID every Element should have a unique id. We can not have more than one same  id in a HTML documents.

We are going to write same above example with id attribute.



```html
<style>
      #cities {
        background-color: lightblue;
        color: black;
        padding: 40px;
        text-align: center;
      }
<style/>

<h1>id Attribute</h1>
    <h2 id="cities">My Cities</h2>
    <p>Click the button to change elements with id name "myHeader":</p>

    <button onclick="myCities()">Change id elements</button>
    <script>
      function myCities() {
        document.getElementById('cities').innerHTML = 'Yours Cities'
      }
    </script>
```



we use id to give style to heading "My Cities" by using  <h2 id="cities">My Cities</h2> and used  #cities when writing CSS for that element.


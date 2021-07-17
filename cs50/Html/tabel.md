## Basic of Table in HTML

The <table> tag defines an HTML table.

The **`<thead>`** HTML defines a set of rows defining the head of the columns of the table.

Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.

By default, the text in <th> elements are bold and centered.

By default, the text in <td> elements are regular and left-aligned.

We can put caption on the table by add <caption> tag in tabel.

```html
<table>
      <caption>
        Ocean and Depth
      </caption>
      <thead>
        <tr>
          <th>Ocean</th>
          <th>Ocean Average Depth</th>
          <th>Ocean Maximun Depth</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Pasfic Ocean</td>
          <td>4,599 m</td>
          <td>10,900</td>
        </tr>

        <tr>
          <td>Atlantic Ocean</td>
          <td>3,876 m</td>
          <td>10,900</td>
        </tr>
     </tbody>
</table>
```

We can give basic styling by adding CSS properties in HTML <head> tag

```css
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
```


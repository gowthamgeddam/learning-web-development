# HTML tables
> A web table is an HTML structure which consists of mutiple table rows with each row containing one or more table cells.

- Tables are block level elements
- The size of the table is defined by the number of rows , cells and content.

## HTML table tags
|tag|details|
|:---:|:---:|
|`<table>`| defines table|
|`<tr>`| defines table row|
|`<th>`| defines a header cell in table|
|`<td>`| defines a cell in the table|

- The above table can be wriiten in html as follows:
```html
<table>
    <tr>
        <th> tag </th>
        <th> details </th>
    </tr>
    <tr>
        <td> <code>&lt;table&gt;</code> </td>
        <td> defines table </td>
    </tr>
    <tr>
        <td> <code>&lt;tr&gt;</code> </td>
        <td> defines a row </td>
    </tr>
    <tr>
        <td> <code>&lt;th&gt;</code> </td>
        <td> defines a header cell in table </td>
    </tr>
    <tr>
        <td> <code>&lt;td&gt;</code> </td>
        <td> defines a cell in the table </td>
    </tr>

</table>
```

## Border attribute
- to the table tag we can give `border` attribute for table borders.
- Eg:
    ```html
    <table border="5px">
        ...
    </table>
    ```
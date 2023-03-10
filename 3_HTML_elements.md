# HTML Elements

## Text level elements
- Appear inline with the surrounding content and are known as inline elements.
    - `<a>` - anchor tag for hyperlinks
    - `<strong>` - format text to appear in **bold**.
    - `<code>` - marks content that represents computer code.
    - `<br>` - represents a line break
    - `<em>` - emphasis tag, for _italics_
    - `<u>` - underlined text
    - `<span>` - used to add hooks to inline text
    - `<q>` - Adds quotation to text
    - `<sub>` - marks text as subscript

## Grouping Elements
- Grouping elements are used to organise similar content in a distinct manner in which content is made uniform.
    - `<blockquote>` - add quotations and indentation to the text.
    - `<div>` - contains a generic group of elements in a html doc.
    - `<hr>` - horizontal line that sepearte the content
    - `<ol>` - ordered list
    - `<ul>` - unordered list
    - `<li>` - list time
    - `<nav>` - marks a list of hypertext or navigation links

## Navigating Web Pages
- `Hypertext` - is created using the anchor tag in combination with the href="URL" attribute , where url is the address of another web page.
- `Navigation` - uses hyperlinking to allow users to navigate between webpages.
- `<nav>` tag defines a set of navigation links.
- often used with `<ul>` unordered list.
- Ex:
    ```
    <nav>
        <ul>
            <li> <a href="index.html"> Home </a> </li>
            <li> <a href="work.html"> Work </a> </li>
            <li> <a href="contact_me.html"> Contact </a> </li>
        </ul>
    </nav>
    ```

## Comments in HTML
- A descriptive text added to the code but is not rendered in browser
- Helps developer understand the code
- to use comment in html, we use the following notation
    ```
        <!--- Comment here --->
    ```

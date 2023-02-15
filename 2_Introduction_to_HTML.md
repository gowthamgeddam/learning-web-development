# Introduction to HTML
> **Do you know?** - "People start watching your website from top left corner"

## HTML
- **Hypertext Markup Language** (`HTML`) is a standard markup language for creating webpages and web apps.
- Invented by `Tim Berners Lee`.
- It enables media files (like images, music, video) to be embedded.
- Semantically defines webpage
- Allows to embed javascript
- Elements have attributes (like color, height, width etc.)
- Now it is `HTML 5`

## Defining a HTML document
- Any html document should have a `.html` extension at the end of their name.
- A basic html doc would look something like the below
    ```
    <!DOCTYPE html>
    <html>
        <head>
            <title>Title of the page</title>
        </head>
        <body>
            <h1>Here we place Heading</h1>
            <p>This is a paragraph</p>
        </body>
    </html>
    ```
- Line 1 above defines that the document is gonna be a html document.
- We have elements/tags in html that encloses the content.
- tags are denoted by angular brackets `<>`
- most of the tags have opening and closing tags.
- Closing tag have `slash` in it like in `</html>`
- `<html>` tag is for the whole html
- `<head>` contains data about the page. Except title, no content that is here is visible on the webpage.
- `<title>` - contains the title/name of the webpage that is shown on the tab name in a web browser and also in search results.
- `<body>` - contains the min content
- `<h1>` - is a heading, that is largest text.
- We have heading tags from `<h1>` to `<h6>`
- `<p>` - is paragraph tag for normal text.

## Common HTML tags
- `<a href="URL"></a>` &larr; anchor tag used for hyperlinks or links simply, and have `href` attribute for which the value will be a url.
- `<div></div>` &larr; a block level element that doesn't add anything to the text but helpful for styling
- `<span></span>` &larr; an in-line element, also for styling
- `<h1></h1>` to `<h6></h6>` - for headings
- `<li></li>` &larr; list item element for lists
- `<img>` &larr; image element
    - it doesn't have closing tag
    - attributes: `src` for source of the image, `alt` an alternative text to show when the image can't be loaded.

## Few other HTML Tags
- `<header>` - specifies header for a document or section that has large texts and headings
- `<nav>` - defines navigational links i.e used with list items.
- `<section>` - defines a section in adocument
- `<article>` - defines an article
- `<aside>` - defines content aside from page content (like sidebars)
- `<footer>` - defines footer for a document, that is found in the bottom of the page.
- `<main>` - specifies the main content of the document
- `<figure>` - specifies self-contained content like diagrams, photos and code etc.

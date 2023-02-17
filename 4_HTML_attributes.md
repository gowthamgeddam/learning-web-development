# HTML atrributes
- Attributes provides additional information about an element and expand the functionality of the elements.
- Attributes control the behaviour of each element.
- **IMPORTANT:**
    + Attributes are always specified in opening tag of the element.
    + Attribute comprises of two parts - a name and a value.
    + Attribute names and values are case sensitive.
- *name* is the property of the element that you want to alter and *value* is .. you know the value of the property.
- **Example:** In the following code `align` is the name of the attribute and `center` is the value.
    ```html
    <p align='center'> This is aligned to center </p>
    ```
## Common Attributes
| Name | Meaning |
| :---: | :---: |
| `id` | Specifies a unique identifier for an element |
| `class`| used to define styles by grouping elements with same class name|
| `href`| Specifies the url (web address) for a link|
| `target`| Specifies where to open the link. Eg: _blank, _self, _parent|
| `style` | Specifies an inline css style for an element|
|`src`|Specifies url or path for an image|
|`alt`|Alternative text for an image, when an image can't be displayed|
|`width`|provide width parameter for elements like photos|
|`height`|provides height parameter for elements|

## Core attributes (id and class)
- **id**
    + must be unique to a sinle element
    + used to reference html elements in css and javascript.
    + Preceded by `#` (hashtag) when being referenced in css.
- **class**
    + can be assigned to one or more elements to group them to have similar charecteristics
    + used to reference html element in css and javscript
    + preceded by `.` (dot/fullstop) when being referenced in css.
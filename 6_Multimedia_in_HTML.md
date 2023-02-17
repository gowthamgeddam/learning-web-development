# Multimedia in HTML

## Images
- We use `<img>` to embed simple image in our webpage.
- Images improves the design and layout of the website.
### Image Attributes
|Attributes|Details|
|:---:|:---:|
|`src`|specifies url or path for an image|
|`alt`|alternative text to show when image can't be displayed|
|`width`|Width of the image|
|`height`|Height of the image|

Eg:
```html
<img src="./img/love_a_lot_more.png" alt="nick vujicic says 'love each other a lot more'">
```
![nick vujicic says "Love each other a lot more"](./img/love_a_lot_more.png)

## Audio
- We use `<audio>` tag to embed audio file in a html page.
### Common Audio attributes
|Attribute|Details|
|:---:|:---:|
|`controls`|specifies audio controls(play/pause etc)|
|`autoplay`|specifies that audio will play as soon as it is ready|
|`loop`|specifies if the audio will play in loop|
|`muted`|specifies that the audio output be muted|
|`src`|specifies the url of the audio file|

> **NOTE:** It is very important that you add atleast `src` and `controls` for the element to load correctly.

- Ex:
    ```html
    <audio src='./audio/Virtual-Piano-3_52_12%20PM.wav' controls>
    ```
<audio src='./audio/Virtual-Piano-3_52_12%20PM.wav' controls>

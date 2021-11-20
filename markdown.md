# HTML Images

Images can improve a design and appearance of a web page.

Example

```html 
<img src= "./cologne_dom.jpeg" alt= "Cologne Dom Cathedral">
```

<img src= "./cologne_dom.jpeg" alt= "Cologne Dom Cathedral">

## HTML Images Syntax 

The HTML `<img>` tag is used to embed an image in a web page.

The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.

The `<img>` tag has a two required attributes:

- src- Specifies the path to the image
- alt- Specifies an alternate text to the image

Syntax

```html
<img src="url" alt="alternatetext">
```

## Image Size -Width and Height

You can us the <span>style </span>attribute to specify the width and height of an image.

Example 

```html
<img src="img_girl.jpeg" alt="Girl in a jacket" style="width:500px;height:600px;">
```

Alternatively, you can use the <span>width</span> and <span>height</span> attributes:

Example

```html 
<img src="img_girl.jpeg" alt="Girl in a jacket" width="500" height="600">
``` 
The <span> width </span> and <span> height</span> attributes always define the width and height of the image in pixels.

## Common Image Formats

Here are the most common image file types, which are supported in all browsers (Chrome, Edge, Firefox, Safari, Opera):

| Abbreviation | File Format                         | File extension             |
|--------------| ------------------------------------|----------------------------|
| APNG         |Animated Portable Network Graphics   |.apng                       |
| GIF          |Graphics Interchange Format          |.gif                        |
| ICO          |Microsoft Icon                       |.gif                        |
| JPEG         |Joint Photographic Expert group image|.jpeg,.jpg,.jfif,.pipeg,.pjp|
| PNG          |Portable Network Graphics            |.png                        |
| SVG          |Scalable Vector Graphics             |.svg                        |

## Rounded Images

Use the border-radius property to create rounded images:

```css
    img {
      border-radius: 50%;
     }
```

<img src= "./cologne_dom.jpeg" alt= "Cologne Dom Cathedral" class="rounded">

<!--custom CSS-->
<style>
 
 h2 {
     border-bottom: 1px solid cyan;
     margin-top: 45px;
     padding-bottom: 20px
 }
span {
    color:red;
}
th{
    color:green;
    text-align: right !important;
}
td {
    color:cyan;
}
.rounded {
    border-radius: 50%;
}
</style>

<!--<img src="./cologne_dom.jpeg" alt= "Cologne dom Cathedral" style="border-radius: 50%;"> -->

Created with :heart:
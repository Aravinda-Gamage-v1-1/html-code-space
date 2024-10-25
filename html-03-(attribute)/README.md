### Attribute 
Html attribute provides additional information about html elements.
* All html elements can have attributes.
* Attribute are always specified in the start tag.
* Attribute usually come in name/value pairs like name = "value".

#### href attribute
The `<a>` tag defined a hyperlink. The href attribute specified the URL of the page link goes to.

`` <a href = "www.w3school.com>Visit W3Schools </a> ``

#### src attribute 
The `<img>` tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be display.

`` <img src = "4.jpg> ``

There are two ways to specify the URL in the src attribute.
1. Absolute URL - Links to an external image that is hosted on another website.
2. Relative URL - Links to an image that is hosted within the website.

#### Width and height attributes
The `<img>` tag should also contain the width and height attributes.

`` <img src = "4.jpg" height = "500px" width = "600px" > ``

#### Alt attribute
The required alt attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason can't be displayed.

`` <img src = "4.jpg" alt = "This is picture" > ``

#### Style attribute
The style attribute is used to add styles to an element, such as color, front size, and more.

`` <p style = "color:red;"> This is paragraph </p> ``

#### Lang attribute
You should always include the lang attribute inside the `<html>` tag, to declare the language of the web page.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Attribute</title>
</head>
<body>
    
</body>
</html>
```

#### Title attribute
The title attribute defined some extra information about an element.

`` <p title = "This is paragraph 01"> This is paragraph </p> ``



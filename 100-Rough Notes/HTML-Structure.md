---
id: HTML-Structure
aliases: []
tags:
  - web-development
---

# HTML-Structure

[[html]] is a markup language that give structure to webpage and it organize the contents in web page, like it determine how should a element look in the web page and what elements there should be in an web page. we can use css to further change the layouts of these contents give responsive design etc.

## Basic Structure

an html document is a series of nested elements that work together to form a complete webpage.

the structure given below is the basic structure for and html5 webpage.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>title</title>
  </head>
  <body>
    <h2>heading content</h2>
    <p>paragraph content</p>
  </body>
</html>
```

1. `<!DOCTYPE html>` this indicates that the document is written in HTML5,
2. `<html></html>` element is the root element of the html document. everything inside this element is considered as part of html document.
3. `<head></head>` is section contains metadata about the document that is not displayed on the webpage.
   - `<meta charset="UTF-8">` : Specifies the character encoding for the document (UTF-8 supports most characters from all languages).
   - `<meta name="viewport" content="device-width, initial-scale=1.0">` : controls the layout on mobile devices by setting the viewport width and scaling.

4. `<body>` tag contains the actual content of the webpage that will be visible to users,such as text,image,and links.

> [!metadata]
> metadata provide essential context,structure,and description for raw data,making it easier for humans and systems to find,manage,understand and use. it is called as data about data.

## Tags and Elements

Tags : these are keywords enclosed in angle brackets that are used to mark the beginning and end of an html element or to define element in html.

Elements : an html element is a component of an html document generally consisting of an opening tag,content,and a closing tag, or a tag that defines a void element. an element will have attributes also which are used to control the element further.

#### element in html

![element in html](https://media.geeksforgeeks.org/wp-content/uploads/20251106164132053975/_p_class_text_hello_world_p_.webp)

> [!NOTE]
> Tags in HTML are structural components used to form elements in HTML, which then form the structure of a web page.

> [!IMPORTANT]
>
> 1. use semantic html : use appropriate tags such as header,footer,article,and section to improve the structure and accessibility of the page.
> 2. include alt text for images

## Reference

[structure of html](https://www.geeksforgeeks.org/html/html-course-structure-of-an-html-document/)

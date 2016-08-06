**WDI Fundamentals Unit 2**

---

# HTML Cheat Sheet

### Elements
* The building blocks of HTML. An element consists of a start tag, content, and end tag.

  * Headline Elements: are meant to be used for important text that titles the content that comes after it. They range from `<h1>` — the largest — to `<h6>` — the smallest.

      ```html
      <h1>This would make a big headline!</h1>
      ```

  * Paragraph Elements: are one of the most basic tags in HTML. They indicate blocks of text.

    ```html
     <p>This would add a block of text to a page</p>
     ```

  * Anchor Elements: are the tags we use to create links. In order to make a working link, we have to add more information to the anchor tag, using an href attribute.

    ```html
    <a href="www.generalassemb.ly"> This would make this whole sentence a link to General Assembly's home page.</a>
    ```

### Tags
* HTML syntax used to indicate to a web browser how to present content. Bookended by angle brackets.

#### Heading Tags
* `<h1>` through `<h6> ` are meant to be used for important text that titles the content that comes after it.

#### Paragraph Tags
* `<p>` tags are one of the most basic tags in HTML. They indicate blocks of text.

#### Anchor tags
*  `<a>` tags are the tags we use to create links. In order to make a working link, we have to add more information to the anchor tag, using an attribute.

### HTML Attributes
* Adds information to an HTML element. An HTML tag can have one or many attributes. Attributes are always included in the opening tag. They are preceded by a space, include the name of the attribute, an equal sign, and a value in quotes.

### HTML Boilerplate

In order to organize tags properly, start with a set of structural elements called the HTML boilerplate. It should look like this:

```html
<!DOCTYPE html>
<html>
     <head>

     </head>
     <body>

     </body>
</html>
```

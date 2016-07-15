**WDI Fundamentals Unit 3**

---

# CSS Cheat Sheet

#### Rule
The building block of a CSS stylesheet. A rule consists of a selector and a declaration block (one or more declarations).

#### Declaration
A declaration is made up of a property and a value, separated by a colon and punctuated by a semi-colon.

#### Selector
The actual HTML object the declaration(s) apply to.

#### Property
The characteristic of the selector that will be changed.

#### Value
The amount or type of change to be applied to the corresponding property of the matched selector.

#### Marking-Up
The process of assigning HTML tags to given text content in order to indicate its relation to the rest of the text or dictate how it should be displayed.

#### Serif Font
One of two general categories of fonts (typefaces) that uses marks (called “serifs”) to embellish characters. A common serif font is “Times New Roman”.

#### Sans-Serif Font
One of two general categories of fonts that have cleaner line due to not using marks to embellish characters. (Sans Serif literally meaning “Without serif”) A common sans-serif font is “Helvetica”.

#### Class
A class attribute is added to an HTML element in order to give you a “hook” to refer to that element in your CSS. CSS class selectors begin with a “.”. Classes can be used multiple times per page.

#### ID
An id attribute is added to an HTML element in order to give you a “hook” to refer to that element in your CSS. CSS id selectors begin with a “#”. IDs can only be used one time per page.

#### Horizontal Rule
Add a horizontal line across your page using the hr tag.

#### Line Break
Break up a block of text using the br tag.

#### Image
Add images to your HTML using the img tag. Tell the browser the source of the image file with an src attribute.

#### Absolute File Path
A path to a website or file that includes a full web address (starting with “http”) that the browser loads from the remote location directly. For example:

`<img src="http://imgur.com/awesomedog.jpg">`

#### Relative File Path
A path to a website or file that gives you the path to the resource you are looking for as it relates to your website's local file structure. For example, if you wanted to retrieve an image called newlogo.png that resides in a file called img, you would enter the following relative address:

`<img src="images/awesomedog.jpg">`

#### Why Separate HTML from CSS?

Separating HTML from CSS offers you scalability and versatility. If you separate how your site looks from what your site says, things become more flexible.

By separating your HTML and CSS, you can make the change in one place and have it apply to your whole site. If you separate what your site says from how it looks, you can apply any number of different styles to the same content.

#### CSS Color Treatment

While color names are fine when you're just beginning, there's a number of reasons you'll want to switch over to something more advanced.

First, color names are rendered differently by different browsers. Secondly, there are only 147 color names accepted as standard, meaning your options are going to be pretty limited.

Instead, you'll want to use either RGB or hexadecimal codes. Both of these are built on a system of entering values for the colors red, green, and blue.

By mixing different intensities of these three colors, you can create millions of different colors and shades. Intensity values range from 0 (no intensity) to 255 (full intensity) in the RGB system.

In hex, they range from 0-9, then continue from A-F, with two characters each for red, green, and blue.
This is clearer with examples, so here are some common colors with their RGB and Hex equivalents.

The format for color names, RGB, and hexadecimal should look like the following, respectively:


```css
p {
     color: red;
}
```

```css
p {
     color: (255,0,0);
}
```

```css
p {
     color: #FF0000;
}
```

#### CSS Text Treatment

**font-family**

To adjust the font of your selected text element, use the font-family property. For the value, enter the name of the font to which you’d like to alter your text. To be safe, add a comma after your selected font and enter a generic family as a fallback. If the web browser doesn’t support the font you selected, it will choose the fallback.

```css
h1 {
     font-family: Arial, sans-serif;
}
```

If your selected font is more than one word, capitalize both words and put them in quotation marks.

```css
h1 {
     font-family: "Courier New", monospace;
}
```

**font-size**

To increase or decrease the spacial dimensions of your chosen text, use the font-size property. As a beginner, you can start by entering pixel values for your font-size values.

```css
h3 {
     font-size: 24px;
}
```

As you become more advanced, you'll probably use percentages, `em`s, or `rem`s more often than you use pixels. These measurements work better for sites that will be viewed on multiple screen sizes. (More on them later!)


**font-weight**

To adjust the thickness of your selected text, use the font-weight property.

You can enter the values “normal” to make your text thin and “bold” to make your text thick. These values aren’t very specific, different browsers may interpret their display with slightly different outputs.

```css
h1 {
     font-weight: normal;
}
```

```css
body {
     font-weight: bold;
}
```

For more granular control, you can use the numbers 100, 200, 300, 400, 500, 600, 700, 800, and 900 as values. With this system, 400 is roughly equivalent to “normal” and 700 roughly equals “bold.”

```css
h1 {
     font-weight: 400;
}

a {
     font-weight: 700;
}
```

**font-style**

To make normal text italic, use the property font-style and the value “italic.” To reverse this effect, use the value “normal.”

```css
a {
     font-style: italic;
}

h3 {
     font-style: normal;
}
```

**text-align**

To adjust the positioning of a text element, use the CSS property text-align and one of the following values: left, right, center, or justify.

```css
body {
     text-align: center;
}
```

**text-decoration**

To add an underline to normal text, use the CSS property text-decoration and the value “underline.”

```css
h1 {
     text-decoration: underline;
}
```

To remove underlines, use the value “none.” This declaration is often applied to anchor tags.

```css
a {
     text-decoration: none;
}
```

Less commonly used values for text-decoration include "overline," which adds a line above text, and "line-through," which strikes a line through your text.

**text-transform**

To adjust capitalization in a selected text element, use the text-transform property.

Values for this property include “uppercase” to make every letter capitalized, “lowercase” to make every letter uncapitalized, and “capitalize” to make the first letter of every word in the selected text uppercase.

```css
h1 {
     text-transform: uppercase;
}
```

#### Classes vs. IDs

Classes and IDs are new selectors to set the style of specific HTML elements on your page.

Classes are for groups of elements. IDs are only capable of styling a single element.

Using these selectors allows you more flexibility and finer control than just using tag name selectors.

#### HTML and Images

When you’d like to add images to your site, you should use the `img` tag with the “src” attribute. “src” stands for “Source” and works just like the tag’s “href” attribute. It tells the image tag where to find the image you’d want to include on your page.

#### Relative vs. Absolute Addressing

Relative addressing basically tells your browser: “Look in our project folder for the file specified. Or, if the reference starts with a folder name, look within that folder for the file specified.”

When we link to a source outside of our project we will use an absolute address.

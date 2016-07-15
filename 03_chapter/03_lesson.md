**WDI Fundamentals Unit 3**
---

#Classes and IDs

You've seen how to use HTML tag names as selectors to attach CSS styles to HTML elements.

```css
p {
  background-color: yellow;
}
```

Selecting elements by tag name has a drawback - you select *every* element with that tag on the page, so your styles apply to *every* element with that tag.  In the example above, every single paragraph on the page gets a yellow background.

There are way more ways to select HTML elements than just by tag name. In the next few sections, you'll learn about using `class` and `id` HTML attributes to target and style more specific HTML elements on your page.

Classes will allow you to select multiple elements, and the elements don't even have to have the same tag name.  IDs are used to style a single element. Using these selectors allows you flexibility and control of styling individual elements as well as groups of elements on your page.

<div class="wistia_responsive_padding" style="padding:56.25% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><iframe src="//fast.wistia.net/embed/iframe/ugwfg1gtqw?seo=false&videoFoam=true" allowtransparency="true" frameborder="0" scrolling="no" class="wistia_embed" name="wistia_embed" allowfullscreen mozallowfullscreen webkitallowfullscreen oallowfullscreen msallowfullscreen width="100%" height="100%"></iframe></div></div>
<script src="//fast.wistia.net/assets/external/E-v1.js" async></script>

#### Checkpoint:

* Why would you choose to use an ID over a Class?
* How do add an ID attribute to an element? What does the corresponding CSS selector look like?
* How do you add a class attribute in HTML? What does a CSS class selector look like?
* Can you use IDs more than once?

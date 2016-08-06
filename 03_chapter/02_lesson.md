**WDI Fundamentals Unit 3**

---

# CSS Color

In this lesson, we'll learn about working with various CSS color and text methods to add flare to our websites. Check out the videos below!

<div class="wistia_responsive_padding" style="padding:56.25% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><iframe src="//fast.wistia.net/embed/iframe/2vazcm3j1l?seo=false&videoFoam=true" allowtransparency="true" frameborder="0" scrolling="no" class="wistia_embed" name="wistia_embed" allowfullscreen mozallowfullscreen webkitallowfullscreen oallowfullscreen msallowfullscreen width="100%" height="100%"></iframe></div></div>
<script src="//fast.wistia.net/assets/external/E-v1.js" async></script>

#### More on CSS Colors

While color names are fine when you're just beginning, there's a number of reasons you'll want to switch over to something more advanced. First, color names are rendered differently by different browsers. Secondly, there are only 147 color names accepted as standard, meaning if you want to be *sure* a color will work, your options are going to be pretty limited. Better systems are RGB or hexadecimal color codes. Both of these are built on a system of entering values for the colors red, green, and blue.

By mixing different intensities of these three colors, you can create millions of different colors and shades. Intensity values range from 0 (no intensity) to 255 (full intensity) in the RGB system. In hex, they range from 0-9, then continue from A-F, with two characters each for red, green, and blue. This is clearer with examples, so here are some common colors with their RGB and Hex equivalents.

The format for color names, RGB, and hexadecimal should look like the following, respectively:

```css
p {
     color: red;
     background-color: green;
}

p {
     color: (255,0,0);
     background-color: (0,255,0);
}

p {
     color: #FF0000;
     background-color: #00FF00;
}
```

#### Opacity

Web developers usually use alpha to change the opacity of an element. See below:

![](../assets/elkwebdesign/rgb.png)

There's also a special "color" called <code>transparent</code> that sets the opacity of an element to 0.


---

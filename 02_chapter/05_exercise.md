**WDI Fundamentals Unit 2**

---

##![Your Turn](../assets/exercise.png) Your Turn

In this exercise, you'll work with **hyperlinks**: those wonderful, clickable links that get you from one place to another on the web!

When complete, your output should look like this:

![](../assets/elkwebdesign/hyperlinks.png)


### Instructions

Use the editor provided below to write your code and see what renders!

<a class="jsbin-embed" href="https://jsbin.com/vuquwe/embed?htmlheight=600px">JS Bin on jsbin.com (reload page if JSBin is not showing)</a><script src="https://static.jsbin.com/js/embed.min.js?3.35.12"></script>


1 . Give your website some content: introduce yourself, mention one social media account (or any website of your choosing), and ask for an email. Something like this should work:

*Hi, I'm awesome.
Follow me on twitter.  
Send me an email.*

2 . Wrap the first line, "Hi, I'm awesome" in *h1 tags*.

3 . Wrap the rest of your content with *paragraph tags*. You'll want to use the paragraph tag on both the second and third line. HTML tags are reusable, so you can use as many of each kind as you need!

4 . Wrap the text "Follow me" in an *anchor element* (with `<a>` and `</a>`).

5 . The opening `<a>` tag needs a <strong>h</strong>yperlink <strong>ref</strong>erence attribute, so the browser knows where to go when the `<a>` is clicked. Go ahead and link to your twitter or other social media page, or to any website you want!

Example:
`<a href="http://twitter.com/GA">Follow me</a> on twitter.`

> **NOTE** One more thing! Sometimes you won't know which link destinations you want until you've finished coding your site. In those cases, you can substitute a hash symbol as a placeholder, like so: `Check out <a href="#">tomorrow's lottery numbers</a>!` This link still shows up, but clicking it just makes the browser jump to the top of the page.

5 . Now, wrap an empty *anchor* tag around the word "email" on the second line.

6 . In the `href`, put `mailto:` in front of your email address. This tells the browser to treat the hyperlink reference as an email address instead of a web page!

`Send me an <a href="mailto:me@email.com">email</a>.`

> **NOTE** HTML pays attention to spaces between tags. Only words should be hyperlinked, not spaces or punctuation.



Click on the **OUTPUT** button to see what your HTML code renders. Try clicking on both anchor elements in the output to see the effects of web page links and mailing links.

---


#### Checkpoint

Make sure you have:

- Made the introductory sentence a top-level heading with a `<h1>` tag and closed it with a `</h1>`tag.
- Wrapped the rest of the content in two paragraphs, or p elements.
- Linked to another web page.
- Created an email link with the proper email or with a  placeholder.

---

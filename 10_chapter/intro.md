**WDI Fundamentals Unit 10**

---

#####By the end of this Unit, you'll be able to:
* Define a function with one or more parameters
* Execute a function within a program or in the console
* Given a function and a set of arguments, predict the output of a function
* Use selectors and methods to access and update HTML using the DOM

---

# Functions

We've had the opportunity to learn the basics of JavaScript including data types and control flow; now it's time to learn functional programming.

**Function** is a term that comes out of mathematics as a relationship between a set of inputs and a set of outputs. You may remember some function notation from high school math classes.

For example, we can imagine a function `f` that takes the input `x` and spits out a single output: `f(x)`.

<br>
<center><img src="../assets/chapter5/function.png"></center>
<br>

If you have a function where the output is double the input, this relationship is written as `f(x) = 2 * x`. We can write out the output (`f(x)`) for various values of `x`:

| x  | f(x) |
|:-: |:-:   |
| -1 | -2   |
| 0  | 0    |
| 1  | 2    |
| 2  | 4    |
| 3  | 6    |


JavaScript Functions, like mathematical functions, perform transformations. They take in input values and return an output value. Luckily, functions and inputs in JavaScript are just going to be variables; we can give them clearer names than `f` and `x`.

For a sneak peek, here's how we might set up and use a JavaScript function that doubles its input.

```js
// set up or "define" the function for a variable input
function double(number) {
  return number * 2;
}

// use or "call" the function with 10 as the input
double(10);
```

A function call is just another kind of JavaScript expression. It evaluates to whatever output the function returns. In the example above, the expression `double(10)` evaluates to 20.

You'll notice most function names are verbs or verb phrases. This is because functions are good for behaviors and actions.  Some other function names are:

- alert
- prompt


# The Document Object Model

In previous units, we've relied on `console.log` and `alert` to give feedback to users. Later in this unit we'll look at how we can provide more meaningful feedback and make our sites more "user friendly" by allowing users to interact with our site and see its contents updated in real time.

Let's take a look at the following HTML page:

```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>To Do List</title>
</head>
<body>
	<h1>Things To Do</h1>
	<ul>
		<li>Call Mom</li>
		<li>Take out the trash</li>
		<li>Return library books</li>
	</ul>
</body>
</html>
```

The browser pulls in this HTML document, parses it, and creates an object model of the page in memory. This model is called the **Document Object Model (DOM)**.

The DOM specifies that the browser should use a **DOM Tree** to structure this model:

![](/assets/chapter5/dom.png)

Each element in the HTML document is represented by a **DOM node**. You can think of a node as a *live object* that you can access and change using JavaScript. When the model is updated, those changes are reflected on screen.

We can get and set attributes for these nodes – perhaps we want to add a class or update styling to change the background color for an element. We can access and change the content – maybe we want to change the text in the third `li` to read "Return library books - DONE!" Or we can even add new nodes to or remove nodes from the page.

Once we get some functions under our belt we'll take a look at how we can use some of JavaScript's "built-in" functions to interact with the DOM and add more complex interactions to our sites.

Ready to dig in? [Let's take a look at functions.](02_lesson.md)

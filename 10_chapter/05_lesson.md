**WDI Fundamentals Unit 10**

---

#Functional JavaScript

Functions can also be used as procedures – miniature, self-contained programs that are executed one line at a time whenever the function is called.

When you have a set of tasks that need to be repeated, it can often be helpful to turn that set of tasks into a function, and call it every time that the procedure should be run.

For instance, let's consider a french toast recipe. Every time a soaked slice of bread is ready to be cooked, we need to:


> Transfer the slices to your frying pan and cook on a medium-low heat until brown on the bottom.
>

Rather than writing out explicitly how this should be done each time, we could write a function, (say `cookSoggyBread()`) to handle this set of instructions for us, and simply call that function any time the bread slices need to be cooked.

**WDI Fundamentals Unit 9**

---

# Conditionals

## `if..else` Statements

Conditional statements are the expressions that allow us to test whether or not to perform some action.

One of these conditionals is an `if` statement. An `if` statement will take in a condition and, if that condition is truthy, will run whatever code you specify. Here's an example of an `if` statement in action.

```javascript
if (x > 10) {
  x += 10;
  y += 10;
}
```

The condition is what's inside the parentheses; if that condition is truthy, the lines of code inside the curly braces (`{...}`) will be evaluated one by one.

Let's take a step back for a minute, and consider something that's closer to our own experience: a flow chart.


A flow chart is a visual diagram telling us how to behave, depending on some set of conditions. If we were to try to draw a flow chart to describe an `if` statement, we might come up with something like this:

![Flow Chart for `If` Statement](../assets/chapter4/flow_chart_if.png)
<br>

As you can see, a person making their way through this diagram would need to make a decision; depending on whether or not our condition is truthy, they would either enter the block of code or skip it over entirely.

`if` can actually be modified in several ways to change its behavior. For instance, adding an `else if` to our `if` statement allows us to specify a second condition to test; however, *this second condition will only be tested if the first condition fails*.

```javascript
if (x > 10) {
  x += 10;
  y += 10;
} else if (x > 5) {
  x += 5;
}
```
<aside style="float: left;">![Flow Chart for `If...Else If` Statement](../assets/chapter4/flow_chart_if-elseif.png)</aside>
<br>
<br>

<p>We can add as many `else if` statements as we want - just keep tacking them on.</p>

```javascript
if (x > 10) {
  x += 10;
  y += 10;
} else if (x > 5) {
  x += 5;
} else if (x > 3) {
  x += 3;
}
```
<aside style="float: left;">![Flow Chart for `If...Else If...Else If` Statement](../assets/chapter4/flow_chart_if-elseif-elseif.png)</aside>
<br>

However, if all of the conditions fail, nothing will happen. To specify behavior for this outcome, we must add an `else` to the end of our statement, like so.

```javascript
if (x > 10) {
  x += 10;
  y += 10;
} else if (x > 5) {
  x += 5;
} else if (x > 3) {
  x += 3;
} else {
  x += 1;
}
```
<aside style="float: left;">![Flow Chart for `If...Else If...Else If...Else` Statement](../assets/chapter4/flow_chart_if-elseif-elseif-else.png)</aside>
<br>

Using `if...else` statements allows us to write code that can behave very differently in different circumstances.

### Test Yourself
Consider following conditional statement:

```javascript
if (x > 5) {
  y = 50;
} else if (x < 5) {
  y = 33;
} else {
  y = 100;
}
```

* What value will be assigned to `y` if ...
  * `x` is 10?
  * `x` is 4?
* Under what circumstances will `y` be assigned a value of 100?

Try copying that whole statement into JS Bin, and testing out different values for `x`. Were your answers correct?


---

[Let's do another exercise.](04_exercise.md)

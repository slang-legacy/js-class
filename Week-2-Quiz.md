#Week 2 Quiz
**Explain how to declare a variable and give it a value in JavaScript.**
You use the syntax `var nameOfVariable = "value (this one's a string)";`. You can also declare multiple variables on the same line with the syntax `var a = 42, b = 'answer to life, the universe, and everything';`.

Assignments are evaluated right to left so this works:
```javascript
foo = bar = 'baz';
foo == 'baz'; //true
bar == 'baz'; //true
```
`bar` gets assigned to the string `'baz'`, then `foo` gets assigned to `bar` (which is `'baz'`)

The `var` statement is actually made to bind variables to the current scope. Without it, the intrepreter tries to assign to an existing variable in the next enclosing scope. This continues until either a variable with that name is found, or it reaches the global scope. This is a dangerous and widely critized feature of the language, thus it is reccomended to always use `var` while making a new variable to reduce the risk of polluting the global namespace.

**Be sure to mention the difference when giving a value to a String vs a number.**

I'm not really sure what you mean with this question. Strings and numbers are both primatives so there isn't really any difference in assigning them.

**Also explain the differences in the three dialog boxes in this unit, Alert, Confirm, and Prompt.**

`alert()` is used for alerting the user with a popup that must be clicked to make it go away. It is also really good at annoying a user - don't use it unless it is absolutely the only way.

`confirm()` Displays a confirmation dialog and returns a value; `true` or `false` depending on the button clicked.

`prompt()` Displays a dialog with a input box and returns the value entered as a string.

It should also be noted that these are not part of any standard, so they may not work in some JS enviroments. Also, these functions are executed synchronously, so your script cannot continue execution until the function returns. In a web-browser, this means that your UI freezes until it is clicked, which is very problematic for webapps.


**And finally explain how and why you might use a parseInt()  when using a prompt.**

`parseInt()` parses a string argument and returns an integer of the specified radix or base

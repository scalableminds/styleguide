# CoffeeScript
* Use [our CoffeeScript compiler](https://github.com/scalableminds/coffee-script). Install with `npm install -g git://github.com/scalableminds/coffee-script.git`

## General
* Carefully examine the project's other code to find out about the applied coding style. Try to mimic the coding style as close as possible.
* Use explanatory identifiers. There's no price for the shortest name. `getFastestReactionSpeed()` is better than `reactionSpeed()`.
* Don't comment out bad/unused code. Delete it.
* Never, ever use `my` prefix for variables, ie. ~~`mySwipe`~~.
* Delete trailing spaces. Linters don't like them anyway. Sublime has an option `trimTrailingWhiteSpaceOnSave`

## Files and Modules
* Use under_score filenames (i.e. `event_mixin.coffee`)
* Files are modules. They need a `define`
* Modules are singleton object, ie. sometimes classes.
* No Javascript file should be included other than through RequireJS.
* External libraries might need to be [shimmed](http://requirejs.org/docs/api.html#config-shim).

## Naming conventions
* Use PascalCase for object/class names (ie. `EventMixin`)
* Use camelCase for variables of all kinds, including methods and function (ie. `isRunning`)
* Use UNDER_SCORE for constants (ie. `BUCKET_LENGTH`). Assign constants as prototype attributes.

## Style
* A method body is followed by two white lines. Between the declaration (parameter list) and body is one white line.
* There are whitespaces around operators including colons, ie. `offset + width` or `challengeId : 2`.
* When commenting an entire method, place the comment under the method declaration (above the white line)
* `value == 0` instead of `!value`
* Use quotation marks (ie. `"string"`) instead of apostrophes (ie. `'string'`) for strings
* Always invoke methods with parentheses (ie. `alert("Hello World")`). Even when passing event handlers.
* Use an explicit `return` statement. Exceptions are small lamdba-esque functions like in `Array#map` (ie. one-liners).
* Omit curly braces for objects if possible, ie. `$el.css( backgroundColor : "#fff" )`.


## Backbone
* Use `listenTo`.
* Use `this.$()` instead of `$()`.




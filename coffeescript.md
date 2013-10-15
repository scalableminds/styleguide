# CoffeeScript
* Use [our CoffeeScript compiler](https://github.com/scalableminds/coffee-script). Install with `sudo bin/cake install`

## General
* Don't comment out bad/unused code. Delete it.

## Files
* Use under_score filenames (i.e. `event_mixin.coffee`)
* Files are modules. They need a `define`
* Modules are singleton object, i.e. sometimes classes

## Syntax
* Use PascalCase for object/class names (i.e. `EventMixin`)
* Use camelCase for variables of all kinds, including methods and function (i.e. `isRunning`)
* Use UNDER_SCORE for constants (i.e. `BUCKET_LENGTH`). Assign constants as prototype attributes.
* A method body is followed by two white lines. Between the declaration (parameter list) and body is one white line.
* When commenting an entire method, place the comment under the method declaration (above the white line)
* `value == 0` instead of `!value`
* Use quotation marks (i.e "string") instead of apostrophes (i.e. 'string') for strings
* Always invoke methods with parentheses (i.e. `alert("Hello World")`). Even when passing event handlers.


## require
* No Javascript file should be included other than through requireJS.
* External libraries might need to be [shimmed](http://requirejs.org/docs/api.html#config-shim).





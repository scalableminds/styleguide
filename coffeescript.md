# CoffeeScript
* Use [our CoffeeScript compiler](https://github.com/scalableminds/coffee-script). Install with `sudo bin/cake install`

## Files
* Use under_score filenames (i.e. `event_mixin.coffee`)
* Files are modules. They need a `define`
* Modules are singleton object, i.e. sometimes classes

## Syntax
* Use PascalCase for object/class names (i.e. `EventMixin`)
* Use camelCase for variables of all kinds, including methods and function (i.e. `isRunning`)
* Use UNDER_SCORE for constants (i.e. `TIMEOUT`). Assign constants as elements of an array.
* A method body is followed by two white lines. Between the declaration (parameter list) and body is one white line.
* `value == 0` instead of `!value`
* Use quotation marks (i.e "string") instead of apostrophes (i.e. 'string') for strings


## require
* No Javascript file should be included other than with requireJS.
* External libraries might need to be [shimmed](http://requirejs.org/docs/api.html#config-shim).





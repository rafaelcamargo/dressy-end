## Naming functions
It is very important to name your functions properly. It's because `Anonymous functions` dificult the reading of your call stack when debugging your code.
So, you have at least two nice ways to keep your functions named:

**1 - Function has a name (obvious way)**
```
function doSomething() {
  ...
}
```

**2 - Function is derived from a named `var`**
```
var doSomething = function() {
  ...
}
```

Both cases will log `doSomething()` on the call stack.

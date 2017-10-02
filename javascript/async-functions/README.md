# web-developer-bootcamp
The Advanced Web Developer Bootcamp

1. Define Callback function


Callback Example:

```
function callback() {
    console.log("Coming from callback");
}

function higherOrderFunction(fn) {
    console.log("About to call callback");

    fn();

    console.log("Callback has been invoked");

}


// calling function

higherOrderFunction(callback);

```

#### A higher order function is a function that accept a callback as a parameter

Callbacks with function Declarations.

```
function greet(name,formatter) {
    return "Hello " + formatter(name);
}

function upperCaseName(name) {
    return name.toUppercase();
}

greet('Tim',upperCaseName);

```




2. Define higher order functions

3.  Use a callback function to make your code more general

4.  Create callbacks using anonymous functions


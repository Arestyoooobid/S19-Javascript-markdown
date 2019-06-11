# 200310824's Multiple Choice Question

## What is the following code an example of?

```js
var arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

function myFunction(arr) {
    var j, x, i;
    for (i = 0; i < arr.length; i++) {
        j = Math.floor(Math.random() * arr.length);
        x = arr[i];
        arr[i] = arr[j];
        arr[j] = x;
    }
    return arr;
}

myFunction(arr);
```

## A function that...

### a) Generates a random array with numbers between 1-10.
### b) Takes in an existing array and shuffles it.
### c) Verifies that each variable in the array corresponds to its .length value.
### d) Was just created to confuse and frustrate you.
The map() method creates a new array with the results of calling a provided function on every element in the calling array.
An Example of map() is:

```
let arr = [1,4,3,6,8];
arr.map(function(x){
  return x*x;
  });
```

Here we are creating a new array, the argument x iterates through the array arr, when we call arr.map(). As an argument of
map, we take a callback function.

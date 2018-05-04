# Analysis of Algorithms

## Exercise I


a) `O(n^3)`

b) `O(log n)`

c) `O((sqrt(n)/2) n^2)` ?

d) `O(n log n)`

e) `O(n^4)`

f) `O(n)`

g) `O(n)`


## Exercise II

a) 
``` js
const maxDiff = (array) => {
    let max = array[0];
    let min = array[0];
    for(let i = 1; i < array.length; i++) {
        max = Math.max(max, array[i]);
        min = Math.min(min, array[i]);
    }
    return max - min;
}
```

b) knapsack algorithm to maximize the number of surviving eggs

c) 

    a) O(n^2) because it would go through its whole process once for every element

    b) O(n log n) because its the ideal case for the alg
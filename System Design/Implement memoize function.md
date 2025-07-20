## Implement memoize function

Memoizes a given function by caching the computed result. Useful for speeding up slow-running computations.

```
// Example usage:
function expensiveCalculation(n) {
  console.log(`Performing expensive calculation for ${n}...`);
  // Simulate a time-consuming operation
  let sum = 0;
  for (let i = 0; i < 1000000; i++) {
    sum += i;
  }
  return n * 2 + sum;
}

const memoizedCalculation = memoize(expensiveCalculation);

console.log(memoizedCalculation(5)); // First call, computes and caches
console.log(memoizedCalculation(5)); // Second call with same argument, returns from cache
console.log(memoizedCalculation(10)); // Third call with different argument, computes and caches
```
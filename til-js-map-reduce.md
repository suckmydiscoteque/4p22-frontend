# JavaScript: map + reduce
Sum squares of numbers.

```javascript
const numbers = [1, 2, 3];
const sumSquares = numbers.map(n => n * n).reduce((a, b) => a + b, 0);
console.log(sumSquares); // 14

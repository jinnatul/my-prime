### isprime
Finds prime numbers using the Sieve of Eratosthenes algorithm.

```js
$ npm i my-prime
```

### Usage
```js
// es5
var pr = require('my-prime');

// es6
import pr from 'my-prime';

pr.isPrime(3);
// => true;

pr.isPrime(4);
// => false;

pr.isPrime(11);
// => true;

pr.isPrime(3079);
// => true;
```
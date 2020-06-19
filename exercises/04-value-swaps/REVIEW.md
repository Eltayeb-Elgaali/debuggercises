# Debuggercises 

## /exercises/04-value-swaps 

> 6/14/2020, 2:03:59 AM 

[../REVIEW.md](../REVIEW.md)

- [/1-double-swap.js](#1-double-swapjs) - _pass_ 
- [/2-triple-swap.js](#2-triple-swapjs) - _pass_ 
- [/3-triple-swap.js](#3-triple-swapjs) - _pass_ 
- [/4-quadruple-swap.js](#4-quadruple-swapjs) - _pass_ 
- [/5-quadruple-swap.js](#5-quadruple-swapjs) - _pass_ 
- [/6-let-and-const.js](#6-let-and-constjs) - _pass_ 
- [/7-let-and-const.js](#7-let-and-constjs) - _pass_ 
- [/stepped-swap-example](./stepped-swap-example/REVIEW.md)
  - [/0-setup.js](./stepped-swap-example/REVIEW.md#0-setupjs) - _pass_ 
  - [/1-store-y.js](./stepped-swap-example/REVIEW.md#1-store-yjs) - _pass_ 
  - [/2-reassign-a.js](./stepped-swap-example/REVIEW.md#2-reassign-ajs) - _pass_ 
  - [/3-use-stored-y.js](./stepped-swap-example/REVIEW.md#3-use-stored-yjs) - _pass_ 

---

## /1-double-swap.js 

> pass 
>
> [review source](./1-double-swap.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
```

```js
'use strict';

let a = 2;
let b = 1;
let temp = null;

// write some code!
temp = a;
a = b;
b = temp;


// fill in the _ to pass the assertions

const isTrue1 = a === 1;
console.assert(isTrue1, 'Test 1');

const isTrue2 = b === 2;
console.assert(isTrue2, 'Test 2');

const isTrue3 = temp === b;
console.assert(isTrue3, 'Test 3');


```

[TOP](#debuggercises)

---

## /2-triple-swap.js 

> pass 
>
> [review source](./2-triple-swap.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
+ PASS: Test 4
```

```js
'use strict';

let a = 3;
let b = 1;
let c = 2;
let temp = null;

// write some code!
temp = a;
a = b;
b = c;
c = temp;


// fill in the _ to pass the assertions

const isTrue1 = a === 1;
console.assert(isTrue1, 'Test 1');

const isTrue2 = b === 2;
console.assert(isTrue2, 'Test 2');

const isTrue3 = c === 3;
console.assert(isTrue3, 'Test 3');

const isTrue4 = temp === c;
console.assert(isTrue4, 'Test 4');


```

[TOP](#debuggercises)

---

## /3-triple-swap.js 

> pass 
>
> [review source](./3-triple-swap.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
+ PASS: Test 4
```

```js
'use strict';

let a = 2;
let b = 3;
let c = 1;
let temp = null;

// write some code!
temp = a;
a = c;
c = b;
b = temp;

// fill in the _ to pass the assertions

const isTrue1 = a === 1;
console.assert(isTrue1, 'Test 1');

const isTrue2 = b === 2;
console.assert(isTrue2, 'Test 2');

const isTrue3 = c === 3;
console.assert(isTrue3, 'Test 3');

const isTrue4 = temp === b;
console.assert(isTrue4, 'Test 4');


```

[TOP](#debuggercises)

---

## /4-quadruple-swap.js 

> pass 
>
> [review source](./4-quadruple-swap.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
+ PASS: Test 4
+ PASS: Test 5
```

```js
'use strict';

let a = 3;
let b = 4;
let c = 1;
let d = 2;
let temp = null;

// write some code!
temp = a;
a = c;
c = temp;
b = d;
d = b + b;



// fill in the _ to pass the final assertions

const isTrue1 = a === 1;
console.assert(isTrue1, 'Test 1');

const isTrue2 = b === 2;
console.assert(isTrue2, 'Test 2');

const isTrue3 = c === 3;
console.assert(isTrue3, 'Test 3');

const isTrue4 = d === 4;
console.assert(isTrue4, 'Test 4');

const isTrue5 = temp === c;
console.assert(isTrue5, 'Test 5');

```

[TOP](#debuggercises)

---

## /5-quadruple-swap.js 

> pass 
>
> [review source](./5-quadruple-swap.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
+ PASS: Test 4
+ PASS: Test 5
```

```js
'use strict';

let a = 3;
let b = 1;
let c = 4;
let d = 2;
let temp = null;

// write some code
temp = d;
d = c;
c = a;
a = b;
b = temp;



// fill in the final _ to pass the assertions

const isTrue1 = a === 1;
console.assert(isTrue1, 'Test 1');

const isTrue2 = b === 2;
console.assert(isTrue2, 'Test 2');

const isTrue3 = c === 3;
console.assert(isTrue3, 'Test 3');

const isTrue4 = d === 4;
console.assert(isTrue4, 'Test 4');

const isTrue5 = temp === b;
console.assert(isTrue5, 'Test 5');


```

[TOP](#debuggercises)

---

## /6-let-and-const.js 

> pass 
>
> [review source](./6-let-and-const.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
+ PASS: Test 4
```

```js
'use strict';

// write code to pass asserts a and b
// fill in the blanks for c and temp

// leave this code as it is
let a = 2;
let b = 1;
let temp = null;

temp = a;
const c = temp;

// write your code below here, and above the assertions
a = b;
b = temp;


// replace the _ with a value to pass the assertions

const isTrue1 = a === 1;
console.assert(isTrue1, "Test 1");

const isTrue2 = b === 2;
console.assert(isTrue2, "Test 2");

const isTrue3 = c === b;
console.assert(isTrue3, "Test 3");

const isTrue4 = temp === c;
console.assert(isTrue4, "Test 4");


```

[TOP](#debuggercises)

---

## /7-let-and-const.js 

> pass 
>
> [review source](./7-let-and-const.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
+ PASS: Test 4
+ PASS: Test 5
```

```js
'use strict';

// write code to pass asserts a, b, c
// fill in the blanks for d and temp

// leave this code as it is
let a = 2;
let b = 3;
let c = 1;
let temp = null;

temp = a;
a = b;
const d = a;
// write your code below here
a = c;
c = b;
b = temp;



// fill in in the _'s to pass the final assertions

const isTrue1 = a === 1;
console.assert(isTrue1, 'Test 1');

const isTrue2 = b === 2;
console.assert(isTrue2, 'Test 2');

const isTrue3 = c === 3;
console.assert(isTrue3, 'Test 3');

const isTrue4 = d === c;
console.assert(isTrue4, 'Test 4');

const isTrue5 = temp === b;
console.assert(isTrue5, 'Test 5');


```

[TOP](#debuggercises)


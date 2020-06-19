# Debuggercises 

> 6/19/2020, 2:28:34 AM 

## [exercises](../../README.md)/[04-value-swaps](../README.md)/stepped-swap-example 

- [/0-setup.js](#0-setupjs) - _pass_ 
- [/1-store-y.js](#1-store-yjs) - _pass_ 
- [/2-reassign-a.js](#2-reassign-ajs) - _pass_ 
- [/3-use-stored-y.js](#3-use-stored-yjs) - _pass_ 
---

## /0-setup.js 

> pass 
>
> [review source](../../../exercises/04-value-swaps/stepped-swap-example/0-setup.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
```

```js
'use strict';

// declare & assign variables
let a = "y";
let b = "x";
let temp = null;

// swap the values stored by a and b ...
temp = a;
a = b;
b = temp;
// assert expected values

const isTrue1 = a === "x";
console.assert(isTrue1, "Test 1");

const isTrue2 = b === "y";
console.assert(isTrue2, "Test 2");

const isTrue3 = temp === "y";
console.assert(isTrue3, "Test 3");

```

[TOP](#debuggercises)

---

## /1-store-y.js 

> pass 
>
> [review source](../../../exercises/04-value-swaps/stepped-swap-example/1-store-y.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
```

```js
'use strict';

// declare & assign variables
let a = "y";
let b = "x";
let temp = null;

// swap the values stored by a and b ...
temp = a;
a = b;
b = temp;

// assert expected values

const isTrue1 = a === "x";
console.assert(isTrue1, "Test 1");

const isTrue2 = b === "y";
console.assert(isTrue2, "Test 2");

const isTrue3 = temp === "y";
console.assert(isTrue3, "Test 3");

```

[TOP](#debuggercises)

---

## /2-reassign-a.js 

> pass 
>
> [review source](../../../exercises/04-value-swaps/stepped-swap-example/2-reassign-a.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
```

```js
'use strict';

// declare & assign variables
let a = "y";
let b = "x";
let temp = null;

// swap the values stored by a and b ...
temp = a;
a = b;
b = temp;

// assert expected values

const isTrue1 = a === "x";
console.assert(isTrue1, "Test 1");

const isTrue2 = b === "y";
console.assert(isTrue2, "Test 2");

const isTrue3 = temp === "y";
console.assert(isTrue3, "Test 3");

```

[TOP](#debuggercises)

---

## /3-use-stored-y.js 

> pass 
>
> [review source](../../../exercises/04-value-swaps/stepped-swap-example/3-use-stored-y.js)

```txt
+ PASS: Test 1
+ PASS: Test 2
+ PASS: Test 3
```

```js
'use strict';

// declare & assign variables
let a = "y";
let b = "x";
let temp = null;

// swap the values stored by a and b ...
temp = a;
a = b;
b = temp;


// assert expected values

const isTrue1 = a === "x";
console.assert(isTrue1, "Test 1");

const isTrue2 = b === "y";
console.assert(isTrue2, "Test 2");

const isTrue3 = temp === "y";
console.assert(isTrue3, "Test 3");

```

[TOP](#debuggercises)


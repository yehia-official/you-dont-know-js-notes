# 🔤 JavaScript Variables

Variables are like containers for storing values.  
They allow us to save data and use it later in our program.

---

## 🔹 Declaring Variables

There are 3 ways to declare a variable in JavaScript:

```js
var name = "Yehia";   // Old way – avoid using it
let age = 22;         // Modern way – can be updated
const country = "Egypt"; // Constant – can’t be changed
````

---

## 🔹 `let` vs `const` vs `var`

| Keyword | Can Reassign | Block Scope | Hoisted | Recommended                     |
| ------- | ------------ | ----------- | ------- | ------------------------------- |
| `var`   | ✅ Yes        | ❌ No        | ✅ Yes   | ❌ No                            |
| `let`   | ✅ Yes        | ✅ Yes       | ❌ No    | ✅ Yes                           |
| `const` | ❌ No         | ✅ Yes       | ❌ No    | ✅ Yes (when value won't change) |

---

## 🔹 Naming Rules

✅ Must start with a letter, `_`, or `$`

✅ Can contain letters, numbers, `_`, `$`

❌ Can't start with a number

❌ Can't use reserved words (like `let`, `if`, `return`)


```js
let userName = "Yehia";   // ✅ Good
let _score = 100;         // ✅ Good
let 1player = "Ali";      // ❌ Invalid
```

---

## 🔹 Dynamic Typing in JavaScript

Variables can change their type depending on the value assigned:

```js
let x = "Hello"; // x is a string
x = 42;          // now x is a number
```

---

## 🔹 Example with Comments

```js
// Declaring a variable using let
let name = "Yehia"; // Name of the user

// Declaring a constant value
const year = 2025; // The current year (won't change)

// Updating a variable's value
let score = 0;
score = score + 10; // Now score is 10
```

---

## 🔹 Why Variables Matter

✅ Store and reuse values

✅ Make your code more readable

✅ Allow user interaction and dynamic behavior

✅ Essential for loops, conditions, and functions

---

## 💡 Pro Tip

Use `const` by default, and only use `let` if you know the value will change.
Avoid `var` — it behaves unexpectedly due to hoisting and lack of block scope.


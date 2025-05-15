## 🔹 What Are Conditionals?

Conditionals let your program **make decisions**.  
Based on a condition, some code runs, and some doesn't.

```js
if (true) {
  console.log("This runs!");
}
````

---

## 🔹 The if / else Statement

```js
let age = 20;

if (age >= 18) {
  console.log("You're an adult!");
} else {
  console.log("You're still young.");
}
```

🧠 The `if` block runs only if the condition is **true**, otherwise the `else` block runs.

---

## 🔹 else if

You can chain multiple conditions using `else if`:

```js
let score = 85;

if (score >= 90) {
  console.log("Excellent!");
} else if (score >= 75) {
  console.log("Good job!");
} else {
  console.log("Keep learning.");
}
```

---

## 🔹 Falsy vs Truthy

JS considers some values as **false** when used in conditions:

```js
// Falsy values:
false, 0, "", null, undefined, NaN
```

Everything else is **truthy**.

```js
if ("hello") {
  console.log("This is truthy");
}
```

---

## 🔹 Ternary Operator

A shortcut for `if/else`:

```js
let access = age >= 18 ? "Allowed" : "Denied";
```

---

## 🔹 Best Practices

✅ Use `===` instead of `==` for comparisons

✅ Don't overuse nested `if` statements

✅ Keep conditions simple and readable

---

## 🔁 Summary

* Use `if`, `else`, and `else if` to control flow
* Know the difference between **truthy** and **falsy**
* Ternary is handy for quick decisions
* Always aim for clean and clear conditions

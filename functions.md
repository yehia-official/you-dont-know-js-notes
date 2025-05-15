
## 🔹 What is a Function?

A **function** is a reusable block of code that does a specific task.

You define it once, then you can run it (call it) whenever you want.

```js
function sayHello() {
  console.log("Hello!");
}

sayHello(); // 👉 prints "Hello!"
````

---

## 🔹 Function Parameters

You can pass data into a function using **parameters**.

```js
function greet(name) {
  console.log("Hi, " + name);
}

greet("Yehia"); // 👉 prints "Hi, Yehia"
```

You can use multiple parameters:

```js
function add(a, b) {
  return a + b;
}

console.log(add(2, 3)); // 👉 5
```

---

## 🔹 Return Values

A function can **return** a value using the `return` keyword.

```js
function square(x) {
  return x * x;
}

let result = square(4); // 👉 16
```

If no `return`, the function returns `undefined` by default.

---

## 🔹 Function Expressions

Functions can also be written as **expressions**:

```js
const sayBye = function () {
  console.log("Bye!");
};

sayBye();
```

---

## 🔹 Arrow Functions (ES6+)

Shorter syntax for writing functions.

```js
const double = (n) => n * 2;

console.log(double(5)); // 👉 10
```

* Great for small, simple functions.
* No own `this` or `arguments`.

---

## 🔹 Why Functions Matter

✅ Reuse code

✅ Break problems into smaller parts

✅ Keep code clean and organized

✅ Support **DRY** (Don’t Repeat Yourself) principle

---

## 📝 Summary

* Functions let you group and reuse logic
* Use `return` to send data back
* Arrow functions = short, clean syntax
* Functions = backbone of clean JS

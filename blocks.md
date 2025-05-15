# 📦 Blocks

---

## 🔹 What is a Block?

In JavaScript, a **block** is a set of statements wrapped in curly braces `{}`.  
Blocks define boundaries for control flow and **scope** (especially with `let` and `const`).

```js
{
  // this is a block
  let a = 5;
  console.log(a);
}
````

---

## 🔹 Where Are Blocks Used?

Blocks are used in:

* `if`, `else`
* `for`, `while`, `switch`
* Functions
* Standalone for creating scopes

```js
if (true) {
  let name = "Yehia";
  console.log(name); // ✅ Works
}
console.log(name); // ❌ ReferenceError
```

---

## 🔹 Block Scope

Before ES6:

* `var` is **function scoped** only (not block scoped).
* So `var` variables leak outside the block.

After ES6:

* `let` and `const` are **block scoped**, meaning they exist only inside `{ }`.

```js
{
  var x = 10;
  let y = 20;
}
console.log(x); // ✅ 10
console.log(y); // ❌ ReferenceError
```

---

## 🔹 Why Block Scope Matters

✅ Helps you avoid variable collisions
✅ Makes your code safer and easier to debug
✅ Encourages better structure & modularity

---

## 🔹 Wrap Up

* `{}` defines a **block**
* `let` and `const` are block-scoped
* `var` is **not** block-scoped
* Prefer `let`/`const` to avoid scope-related bugs

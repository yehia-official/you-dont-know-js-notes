# 📝 JavaScript Code Comments

Writing clean and understandable code is a key skill for every developer — and comments play a big role in that.  
They don’t affect how the code runs, but they help others (and your future self!) understand what’s going on.

---

## 🔹 Single-line Comments

Use `//` to write a comment on a single line.

```js
// This is a single-line comment
let age = 25; // Storing user's age
````

---

## 🔹 Multi-line Comments

Use `/* ... */` for comments that span multiple lines.

```js
/*
  This is a multi-line comment.
  It’s useful for explaining more complex logic or giving detailed notes.
*/
let name = "Yehia";
```

---

## 🔹 Why Use Comments?

✅ To explain **what** your code does

✅ To describe **why** something is written a certain way

✅ To add TODOs or notes for future changes

✅ To leave warnings or hints for tricky logic


---

## 🔹 Practical Example

```js
// Step 1: Get user's age
let age = 18;

// Step 2: Check if the user is eligible to drive
if (age >= 18) {
  console.log("You can drive 🚗"); // Allowed to drive
} else {
  console.log("Too young to drive ❌"); // Not allowed
}

/*
  Note:
  Legal driving age may vary by country,
  but we’re assuming 18 for this example.
*/
```

---

## 🔹 Best Practices

🟢 Write comments that explain **why**, not just **what**

🟢 Keep them short, clear, and helpful

🔴 Avoid obvious comments like:


```js
let x = 5; // assigning 5 to x ❌ (we can already see that)
```
---

## 📌 Final Tip

Comments are powerful — use them to **communicate**, not just annotate.
Your future self will thank you! 💡

---


## 🔹 What is a Loop?

A **loop** is a way to repeat a block of code multiple times.  
Instead of writing the same code again and again, loops automate repetition.

---

## 🔹 for Loop

```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}
````

➡️ This prints: `0 1 2 3 4`

* `i = 0` → start
* `i < 5` → condition
* `i++` → increment

---

## 🔹 while Loop

```js
let count = 0;

while (count < 3) {
  console.log(count);
  count++;
}
```

➡️ Repeats **as long as** the condition is true.

---

## 🔹 do...while Loop

```js
let num = 1;

do {
  console.log(num);
  num++;
} while (num <= 3);
```

💡 `do...while` runs **at least once**, even if the condition is false.

---

## 🔹 Loop Control: break & continue

### `break`: Exit the loop early

```js
for (let i = 0; i < 10; i++) {
  if (i === 5) break;
  console.log(i); // prints 0 to 4
}
```

### `continue`: Skip current iteration

```js
for (let i = 0; i < 5; i++) {
  if (i === 2) continue;
  console.log(i); // skips 2
}
```

---

## 🔹 Looping Through Arrays

```js
let colors = ["red", "green", "blue"];

for (let i = 0; i < colors.length; i++) {
  console.log(colors[i]);
}
```

Or using `for...of` (ES6+):

```js
for (let color of colors) {
  console.log(color);
}
```

---

## 🔁 Summary

* `for`, `while`, and `do...while` help repeat code
* Use `break` to exit early, `continue` to skip
* Loops + arrays = powerful data processing

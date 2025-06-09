# 📝 Todo App

A simple yet stylish **Todo List App** built using **HTML**, **CSS**, and **JavaScript**. This app features local storage for persistence, clean retro-inspired fonts, and supports adding, editing, and deleting tasks with responsive design.

---

## 🌟 Features

- Add new todo items
- Edit existing todos directly in the UI
- Delete todos
- Persistent data using `localStorage`
- Responsive layout for different screen sizes
- Retro aesthetic using **Press Start 2P** font

---

## 🎨 Fonts Used

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=Press+Start+2P&display=swap"
  rel="stylesheet"
/>
```

- `Inter` for modern readability
- `Press Start 2P` for a retro gaming vibe

---

## 💡 Steps in JavaScript

1. **Initialize** the list of todos and display them
2. **Add Todo** — Add a new item to the list
3. **Delete Todo** — Remove a specific item
4. **Edit Todo** — Update the value of an item in-place
5. **Persist Data** — Save todos to `localStorage`

```js
function saveData() {
  // make use of localStorage
  localStorage.setItem("todo-list", JSON.stringify({ todo_list }));
}
```

---

## 📁 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/todo-app.git
   cd todo-app
   ```

2. Open `index.html` in your browser.

3. Start typing your tasks and enjoy!

---

## 📱 Responsive Design

```css
@media (min-width: 640px) {
  header button,
  header input {
    font-size: 1.2em;
  }

  p {
    font-size: 1em;
  }
}
```

---

## ✅ Tech Stack

- HTML
- CSS (in `<style>` block)
- JavaScript (in `<script>` block)
- Browser LocalStorage

---

## 📌 Note

This project does not require a backend or external libraries. All data is stored in the browser.

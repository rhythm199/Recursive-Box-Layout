# Recursive Box Layout

This project demonstrates how to create a dynamic and responsive box layout using only JavaScript **recursion**—without any `for`, `map`, `filter`, or array-related iteration methods. Also has the iterative approach with commented code.

![Screenshot from 2025-04-08 21-45-02](https://github.com/user-attachments/assets/bafe1375-cee7-498a-a2f1-78a8bfd6c0f0)

---

## 🔧 Features

- Accepts an input number `n` and dynamically generates a visual layout:
  - First row: `n` boxes of equal width
  - Second row: `n-1` boxes, each wider
  - ...
  - Last row: 1 box of full width
- Recursive logic for generating rows and boxes
- Real-time layout update on input change
- Border conflict handling between boxes for clean UI

---

## 📂 Project Structure

```bash
index.html    # Main file containing HTML, CSS and JavaScript logic
```

---
## 💻 Technologies Used

- **HTML5**: For basic structure and layout
- **CSS3**: For styling and responsive design
- **Vanilla JavaScript (ES6)**:
  - DOM manipulation
  - Recursive logic
  - Event handling
- **Git & GitHub**: Version control and code hosting

---

## 🛠️ How to Use
1. Clone the repository:
```bash
git clone https://github.com/rhythm199/Recursive-Box-Layout.git
cd Recursive-Box-Layout
```
2. Open index.html in your browser.
3. Enter a number greater than 0 in the input field — the layout will render automatically.

---
## 📘 What I Learned
* Implementing recursive logic for DOM creation
* Creating layouts dynamically without using any loops
* Managing box dimensions and layout spacing
* Resolving border collision issues between adjacent boxes
* Attaching and managing input events


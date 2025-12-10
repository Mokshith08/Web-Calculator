# 📌 Calculator Web App

![HTML Badge](https://img.shields.io/badge/HTML-5-orange?logo=html5)
![CSS Badge](https://img.shields.io/badge/CSS-3-blue?logo=css3)
![JS Badge](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)

A simple, modern, responsive **Calculator** built using **HTML**, **CSS**, and **JavaScript**.  
Supports both **button clicks** and **keyboard input** with real-time display updates.

---

## 🚀 Features

- Performs basic arithmetic operations: `+`, `-`, `*`, `/`
- Supports decimal inputs
- **AC** – Clear all  
- **DEL** – Delete last character  
- **=** – Evaluate the expression  
- Fully responsive UI  
- Smooth hover animations  
- **Keyboard Controls**  
  - Numbers: `0–9`  
  - Operators: `+ - * / .`  
  - `Enter` → Evaluate  
  - `Backspace` → Delete last character  
  - `Escape` → Clear input  

---

### 📁 Project Structure

```txt
.
├── cal.html        # Main calculator UI & logic
├── calc.css        # Stylesheet
└── img/
    └── icon.png    # Favicon (optional)
```
 
---

## 🖥️ How to Run

No installation required:

1. Download or clone the project.
2. Make sure `cal.html` and `calc.css` are in the same folder.
3. Double-click **cal.html** to open it in your browser.

---

🧠 JavaScript Logic Summary

- All button clicks are captured using `querySelectorAll("button")` .
- Input is stored in a variable `input` .
- The display updates dynamically using a helper function.
- Full keyboard support is added using a `keydown` event listener.
- Expression evaluation uses `eval(input)` .

---

📱 Responsive Design

- Fully adaptive layout for mobile screens.
- Buttons resize and reposition dynamically.
- Dark-themed, modern, minimal interface

---

📜 License

This project is open-source and free to modify.

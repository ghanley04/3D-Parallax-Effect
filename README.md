# Parallax Application

This project is a simple **Parallax Effect Application** developed in JavaScript. The goal of this project is to demonstrate the ability to create engaging and visually appealing scrolling effects using HTML, CSS, and JavaScript. The application is not intended as a functional website but as a sandbox to practice and showcase coding skills.

---

## Features

- Smooth parallax scrolling effect.
- Layered backgrounds that move at different speeds to create depth.
- Responsive design for various screen sizes.
- Lightweight and simple implementation using vanilla JavaScript.

---

## Technologies Used

- **HTML5**: Structure of the page.
- **CSS3**: Styling and layout.
  - Utilized properties like `transform`, `position`, and `perspective`.
- **JavaScript (ES6)**: Core functionality for parallax scrolling.
  - Event listeners for `scroll` and window updates.
  - Dynamic adjustments to layer positions based on user input.

---

## How It Works

1. **HTML Structure**:
   - Each parallax layer is represented as a `<div>` with a `data-speed` attribute.
   - The `data-speed` attribute determines how fast the layer moves relative to the scroll position.

2. **CSS Styling**:
   - Layers are styled with `position: absolute` or `fixed` to allow independent movement.
   - A combination of background images and colors creates a layered effect.

3. **JavaScript Logic**:
   - A scroll event listener calculates the scroll position.
   - Each layer’s position is adjusted dynamically based on its `data-speed` value.

---

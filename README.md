# 🎲 Dice-Roller

[![Made with HTML, CSS & JS](https://img.shields.io/badge/Made%20with-HTML%2C%20CSS%2C%20JS-orange.svg?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web)
[![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg?style=for-the-badge)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

Welcome to the **Dice-Roller**, a fun, minimal, and interactive web application built using **HTML**, **CSS**, and **JavaScript**. This project lets you simulate the roll of a six-sided dice — just like in real life! Whether you're learning frontend development or looking for a mini-game to add to your portfolio, this is a great place to start.

---

## 📑 Table of Contents

- [🚀 Live Demo](#-live-demo)
- [🎮 Features](#-features)
- [⚙️ How It Works](#️-how-it-works)
- [🧠 Concepts Covered](#-concepts-covered)
- [📂 Project Structure](#-project-structure)
- [📷 Screenshots](#-screenshots)
- [📦 Technologies Used](#-technologies-used)
- [💻 Getting Started](#-getting-started)
- [🙌 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)

---

## 🚀 Live Demo

👉 [Click here to play it live](#)  
_(Optional: Add GitHub Pages link here if hosted online)_

---

## 🎮 Features

✅ Clean and responsive UI  
🎲 Random dice number from 1 to 6  
🖼️ Dice face updates dynamically using images  
📱 Fully responsive – works on mobile and desktop  
⚡ Lightning-fast with zero dependencies  
👨‍🏫 Beginner-friendly code structure  
🧩 Perfect for small JavaScript projects or code challenges

---

## ⚙️ How It Works

1. When the user clicks the **“Roll Dice”** button:
   - A random number is generated using `Math.floor(Math.random() * 6) + 1`.
   - The corresponding dice image is selected (e.g., `dice1.png`, `dice2.png`, etc.).
   - The image on the screen is updated to reflect the new roll.
   - A message may also appear showing the result.

2. The logic is written entirely in vanilla JavaScript without any libraries.

3. The dice visuals are represented by image files stored locally, and styled with CSS to maintain layout and responsiveness.

---

## 🧠 Concepts Covered

This project is great for understanding and practicing:

- ✅ Basic HTML structure and semantics
- 🎨 CSS styling, alignment, layout techniques
- 🧠 DOM Manipulation in JavaScript
- 🔁 Handling click events
- 🧮 Using `Math.random()` and `Math.floor()` for number generation
- 🖼️ Updating HTML elements dynamically
- 📱 Making websites responsive

---

## 📂 Project Structure

```
22-Dice-Roll-Simulator/
│
├── index.html         # HTML layout and elements
├── style.css          # Styling for dice, button, layout
├── script.js          # JavaScript logic for rolling dice
├── images/            # Folder containing dice face images
│   ├── dice1.png
│   ├── dice2.png
│   ├── ...
│   └── dice6.png
└── README.md          # This file
```

---

## 📷 Screenshots

> 📸 **Add your screenshots below** to showcase the game

### 🎲 Initial State
![Initial screen](./screenshots/initial.png)

### 🎯 After Rolling
![After rolling the dice](./screenshots/after-roll.png)

> _Place your images in a `/screenshots` folder and update the path above accordingly._

---

## 📦 Technologies Used

| Technology | Description |
|------------|-------------|
| 🧱 HTML5    | Page structure and content |
| 🎨 CSS3     | Layout, fonts, images, and responsiveness |
| ⚙️ JavaScript | Dynamic functionality and interactivity |

---

## 💻 Getting Started

Follow these steps to get the project running on your local machine:

### 🔧 Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- Basic understanding of HTML/CSS/JS (recommended)

### 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/he-is-talha/html-css-javascript-games.git
   ```

2. **Navigate to the Dice Roll Simulator directory**
   ```bash
   cd html-css-javascript-games/22-Dice-Roll-Simulator
   ```

3. **Open the project in your browser**
   ```bash
   start index.html   # On Windows
   open index.html    # On macOS
   ```

Or simply **drag and drop** `index.html` into your browser.

---

## 🙌 Contributing

We welcome contributions of all kinds! Here’s how you can help:

1. **Fork this repository**  
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Commit your changes**
   ```bash
   git commit -m "Add a cool feature"
   ```

4. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request** – we’ll review and merge it!

---

## 📄 License

This project is licensed under the [MIT License](../LICENSE). You are free to use, modify, and distribute it for personal and commercial purposes.

---

## 📬 Contact

[shodhanshetty12](https://github.com/shodhanshetty12)

Have suggestions or want to collaborate? Feel free to open an issue or pull request!

---

> 💡 *Don't forget to ⭐ star the repo if you found it helpful!*

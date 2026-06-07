# ⚽ Football Penalty Shootout Game

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Welcome to the **Football Penalty Shootout Game**! This is a lightweight, interactive web-based mini-game where players test their striker skills against an AI goalkeeper. Built entirely with vanilla web technologies, it features clean UI design, responsive layouts, and simple dynamic game logic.

---

## 🎮 Live Demo

> 🔗 **[Click here to play the live game!](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)** *(Replace with your actual live link)*

---

## ✨ Features

* **Interactive Aiming:** Click on different zones inside the goalpost (Top, Bottom, Corners, or Center) to place your shot.
* **Smart AI Goalkeeper:** The keeper simultaneously dives into a random target zone to save your shot.
* **Dynamic Scoreboard:** Tracks your **Goals**, **Saves**, and total **Shots** in real-time.
* **Fluid CSS Animations:** Features smooth transitions for the ball flight and animated goalkeeper dives.
* **Fully Responsive:** Looks and works great on both desktop monitors and mobile screens.

---

## 🛠️ Tech Stack

This project is built using pure, vanilla web technologies with no external dependencies, libraries, or frameworks required:

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Structure of the stadium pitch, goalpost, ball, and scoreboard. |
| **CSS3** | Visual styling, stadium backdrop grid, layout alignment, and dive/shoot animations. |
| **JavaScript (ES6+)** | Game state management, random AI decision logic, scoring system, and UI updates. |

---

## 🚀 How to Play

1. **Launch the game** by opening `index.html` in any modern web browser.
2. **Choose your target:** Hover and click on any of the 5 target boxes inside the goalpost.
3. **Take the penalty:** Watch the ball fly towards your target.
4. **Beat the keeper:** The goalkeeper will dive at the exact same time. If they match your target zone, it's a **SAVE**! If you shoot where they didn't dive, it's a **GOAL**!
5. Use the **Reset Game** button to clear the scoreboard and start a fresh session.

---

## 📂 Project Structure

```text
├── index.html          # Main HTML structure and game layout
├── style.css           # Styling, layout design, and animation keyframes
├── script.js          # Game logic and interactive functionality
└── README.md           # Project documentation

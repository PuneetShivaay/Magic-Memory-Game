# 🃏 Magic Memory Game

[![Live Demo](https://img.shields.io/badge/Demo-Play_Live-2ea44f?style=flat-square&logo=githubpages&logoColor=white)](https://puneetshivaay.github.io/Magic-Memory-Game/)
[![Video Walkthrough](https://img.shields.io/badge/YouTube-Watch_Video-red?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=EZTPC4R_phQ)
[![Medium Article](https://img.shields.io/badge/Medium-Read_Article-black?style=flat-square&logo=medium&logoColor=white)](https://puneetshivaay.medium.com/how-to-play-the-magic-memory-game-af3e2d838035)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![React](https://img.shields.io/badge/Frontend-React.js-61DAFB?style=flat-square&logo=react&logoColor=black)](https://reactjs.org/)

An interactive, responsive card-matching memory game built using React. Players flip two cards per turn, aiming to remember positions and match identical pairs in the fewest attempts possible.

---

## 🔗 Quick Links

- 🎮 **Live Demo:** [Play Magic Memory Game](https://puneetshivaay.github.io/Magic-Memory-Game/)
- 🎥 **Video Demo & Walkthrough:** [Watch on YouTube](https://www.youtube.com/watch?v=EZTPC4R_phQ)
- 📝 **Gameplay & Guide:** [Read on Medium](https://puneetshivaay.medium.com/how-to-play-the-magic-memory-game-af3e2d838035)

---

## 📸 Screenshots & Gameplay

![image](https://github.com/PuneetShivaay/Magic-Memory-Game/assets/56409021/ad51abbf-4ea1-47a1-aaa3-fbaef508a108)

---

## ✨ Features

- 🔀 **Randomized Card Shuffling:** Every round duplicates, shuffles, and assigns unique IDs to the card deck.
- 🔄 **Turn Counter:** Tracks user turns dynamically to measure accuracy and recall speed.
- ⏱️ **Smooth Card Flip Animations:** Realistic 3D card flips styled with CSS keyframes and transitions.
- 🚫 **Click Lockout / Anti-Cheat:** Disables card interaction while an active pair is being compared to prevent spam clicking.
- 📱 **Responsive Layout:** Clean CSS grid presentation adaptable across mobile, tablet, and desktop viewports.
- 🚀 **Zero-Config Deployment:** Deployed and hosted directly via GitHub Pages.

---

## 🛠️ Tech Stack

- **Library / Framework:** React.js (Hooks: `useState`, `useEffect`)
- **Styling:** CSS3 (Flexbox, Grid, 3D Transforms, Transitions)
- **Deployment:** GitHub Pages (`gh-pages`)

---

## 🎮 How to Play

1. Click the **"New Game"** button to shuffle the deck and reset the turn counter to `0`.
2. Click on any card to reveal its front face.
3. Select a second card:
   - **Match:** Both cards remain face-up.
   - **Mismatch:** Both cards automatically flip face-down after a short delay.
4. Continue until all matching pairs are uncovered!

---

## 🚀 Getting Started Locally

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### 1. Clone the Repository
```bash
git clone https://github.com/PuneetShivaay/Magic-Memory-Game.git
cd Magic-Memory-Game
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start the Development Server
```bash
npm start
```
Runs the app in development mode at [http://localhost:3000](http://localhost:3000).

### 4. Build for Production
```bash
npm run build
```

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.



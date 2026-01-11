# Spelling AB - Mobile Edition

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/Platform-Mobile%20Web-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square" alt="License" />
</p>

A mobile-first, sci-fi themed English spelling puzzle game. Designed to feel like a native app with a "Cyberpunk" aesthetic.

## 🎮 Play Now
**[點擊這裡開始遊玩 (Live Demo)](https://simonpaullai.github.io/spellingab-m/)**
*(如果不正確，請將此連結替換為你實際的 GitHub Pages 網址)*

---

## ✨ Features

* **📱 Mobile-First Design**: Optimized viewport settings prevent zooming, offering a native "App-like" experience on mobile browsers.
* **⌨️ Native Keyboard Integration**: Uses a "Hidden Input" technique to trigger the phone's native keyboard while keeping the custom UI.
* **🎨 Dynamic Visual Feedback**:
    * 🟦 **Blue**: Correct Letter & Position.
    * 🟨 **Yellow**: Correct Letter, Wrong Position.
    * 🟥 **Red**: Incorrect Letter.
    * ⬜ **White Dashed Border**: Special indicator for letters that appear **multiple times** in the word.
* **📊 Interactive Dashboard**: A QWERTY display board that lights up to track your used letters (Blue/Yellow/Red status persistence).
* **📚 Level System**: Selectable difficulty from Level 1 to Level 6, powered by a 5,000+ word database (`5kVoc.json`).

## 🛠 Tech Stack

* **HTML5 & CSS3**: Custom Flexbox/Grid layouts, CSS Variables for theming, and responsive design.
* **Vanilla JavaScript**: Zero dependencies. Lightweight and fast.
* **Data Source**: JSON-based vocabulary list (`5kVoc.json`) sourced from CEEC.

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/simonpaullai/spellingab-m.git](https://github.com/simonpaullai/spellingab-m.git)

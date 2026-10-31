<div align="center">

# HunterShell🏹👻

> **Every story leaves something behind.**  
> Where forgotten stepwell folklore meets open-weight artificial intelligence.

<br>

### 🌐 [Live Demo](https://maitriii08.github.io/HunterShell/) &nbsp;•&nbsp; 📦 [GitHub Repository](https://github.com/maitriii08/HunterShell)

</div>

---

## 🌑 About the Project

**HunterShell** is an atmospheric horror storytelling experience inspired by eerie regional folklore, unexplained encounters, and stories passed down through generations across Gujarat and Saurashtra.

Set against the haunted atmosphere of dry stepwells and abandoned salt-merchant havelis, the project explores a simple question:  
*What happens when the stories we inherit begin answering back?*

HunterShell combines interactive storytelling, dark visual design, and an AI-powered ghost conversation experience where visitors can explore unsettling tales and ask questions about the mysteries within them.

---

## ✨ Features

* **📖 Atmospheric Horror Stories:** Explore unsettling regional tales including *The Seventh Lamp*, *The Voice Under the Peepal*, and *The Salt Merchant's Dice*.
* **👻 Grounded Spirit Chat:** Ask questions about the stories. The ghost is strictly instructed to answer **only** from facts present in the tale. If it does not know, it replies honestly: `"The elder never told me that."`[cite: 8]
* **🕯️ Interactive Flashlight Torch:** Experience a dark interface where mouse or touch interactions cast a lantern beam to uncover the text.
* **⚡ Procedural Jump Scare & Gentle Mode:** Features an introductory warning screen with an optional "Gentle Mode" for visitors sensitive to sudden scares[cite: 8, 10].
* **🎵 Pure Web Audio Ambient Drone:** Synthesizes low-frequency atmospheric sound directly inside the browser using the Web Audio API without requiring external audio asset files.
* **🩸 Depleting Courage Gauge:** A live courage bar at the top of the viewport drains as you scroll deeper into the darker tales.

---

## 🛠️ Technology Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5 & CSS3** | Parchment cards, radial torch mask, scanline effects |
| **Vanilla JavaScript** | Grounded Q&A engine, touch/mouse flashlight tracking |
| **Web Audio API** | Real-time procedural ambient drone synthesis |
| **Hosting** | GitHub Pages |

---

## 🧩 How It Works

1. **The Storytelling Interface:** The frontend presents the horror stories shrouded in darkness, requiring user interaction to illuminate each paragraph.
2. **The Grounded Inference Layer:** When a visitor submits a question, the local engine checks the query against the tale's established facts. If a detail was not in the original story, the ghost refuses to hallucinate names or events, answering: `"The elder never told me that."`[cite: 8]

---

<div align="center">

### 🏆 Hacktoberfest 2026 Submission

Built for the **Hacktoberfest Open-Source AI Challenge Week 4: Ghost in the Machine**.  
**Partner Categories:** Best Use of Gemma • Best Use of GitHub Copilot

</div>

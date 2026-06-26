# ⚔️ Demon Slayer RPG: Tactical Battle Engine 👹

Welcome to the **Demon Slayer RPG Battle Prototype**, a lightweight, high-stakes tactical combat simulator built inside a single-file web architecture. Choose your faction, manage your breathing/blood arts, and see how long you can survive an adaptive, scaling threat.

## 🚀 Live Demo
Play the prototype directly in your browser here:  
👉 **[Launch Demon Slayer RPG](https://jrrouth.github.io/Demon-Slayer-RPG/)**

---

## 💡 The Core Concept

The core idea of the game is to provide a fast-paced, choice-driven roguelike battle loop where every decision matters. Instead of mindless hacking and slashing, players must read the battlefield, anticipate their opponent's AI patterns, and manage their finite **Breath Points (BP)** to stay alive.

### Dual-Faction Progression
Players are not locked into one point of view. The engine allows you to experiment with completely different playstyles by choosing your path on launch:

* **The Demon Slayer Route:** Focuses on pure discipline, posture management, tactical blocking, and high-risk, high-reward parry timings to execute enemies.
* **The Rogue Demon Route:** Focuses on raw, brutal offensive power coupled with forbidden Blood Arts that allow you to regenerate tissue and patch your wounds mid-combat.

---

## 🧠 Adaptive Rogue-like Loop Features

* **Stance-Aware AI:** The computer isn't a brainless punching bag. If you try to blindly spam counter-stances, the AI will anticipate the trap, back off, and use a concentration focus move to deliberately waste your turn and BP.
* **Execution Matrix:** When your health drops below 35%, the opponent enters an aggressive execute state, prioritizing devastating ultimate attacks.
* **Endless Tier Scaling:** Every victory pushes you into the next tier. Opponents reset, your maximum BP refreshes, and the enemy's damage output scales up by **+20% per win streak level**. 

---

## 🤝 Credits & Acknowledgments

A massive shoutout to my friend **Rudransh**! 

> This project, its unique faction ideas, and the underlying concept of balancing tactical slayers against evolving demon threats wouldn't have come together without his insight and collaborative inspiration. 

---

## 🛠️ Tech Stack & Local Setup

* **Language:** Pure Vanilla HTML5, CSS3, and JavaScript (ES6+).
* **Database Ready:** Structured cleanly to easily hook up to a Supabase backend for global leaderboards and user authentication.

### How to Run Locally:
1. Clone this repository.
2. Open the `index.html` file directly in any modern web browser.
3. Choose your path and see how high of a win streak you can achieve!

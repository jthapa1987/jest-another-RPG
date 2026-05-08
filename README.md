# 🧙‍♂️ Jest Another RPG

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen)](https://nodejs.org/)
[![npm version](https://img.shields.io/badge/npm-v9.0.0-blue)](https://www.npmjs.com/)
[![Jest](https://img.shields.io/badge/tested%20with-Jest-99424f)](https://jestjs.io/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> **A command‑line role‑playing game built with Node.js, Object‑Oriented Programming, and Test‑Driven Development.**

---

## ✨ Features

- 🎮 **Turn‑based combat** – Battle goblins, orcs, and skeletons.
- 💊 **Potion system** – Collect and use health, strength, or agility potions.
- 🧠 **Character inheritance** – `Player` and `Enemy` extend a base `Character` class (ES6).
- 🧪 **Fully tested** – Every class is verified with Jest unit tests.
- 🖥️ **Interactive CLI** – Powered by `inquirer` for smooth prompts.

---

## 🚀 Live Demo

This is a CLI game — no hosted demo, but you can run it locally in seconds:

```bash
git clone https://github.com/jthapa1987/jest-another-RPG.git
cd jest-another-RPG
npm install
npm start

📦 Installation
# Clone the repository
git clone https://github.com/jthapa1987/jest-another-RPG.git

# Navigate into the project
cd jest-another-RPG

# Install dependencies
npm install

🎮 How to Play
Run node app.js

Enter your character name.

Choose Attack or Use potion on your turn.

Defeat all three enemies to win!

Each defeated enemy drops a potion to aid you in the next battle.


🧪 Running Tests
npm test

All test suites are written with Jest and can be run in watch mode:
npm test -- --watch

🏗️ Project Structure
├── lib/
│   ├── Character.js      # Base class (health, attack, reduce health)
│   ├── Player.js         # Extends Character, adds inventory & potions
│   ├── Enemy.js          # Extends Character, adds weapon & description
│   ├── Potion.js         # Potion types and values
│   └── Game.js           # Game loop, turn order, battle logic
├── __tests__/            # Jest unit tests for all classes
├── app.js                # Entry point
├── package.json
└── README.md


👨‍💻 Author

Jeeva Thapa
https://img.shields.io/badge/GitHub-jthapa1987-181717?logo=github
https://img.shields.io/badge/LinkedIn-connect-blue?logo=linkedin
https://img.shields.io/badge/Portfolio-live-green
📜 License

# 🧙‍♂️ Jest Another RPG

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen)](https://nodejs.org/)
[![npm version](https://img.shields.io/badge/npm-v9.0.0-blue)](https://www.npmjs.com/)
[![Jest](https://img.shields.io/badge/tested%20with-Jest-99424f)](https://jestjs.io/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

# 🚀 Space Miner Game (Pygame)

A simple **strategy-based space mining game** built using **Pygame and Python**.
The player controls a mining spaceship and must collect minerals from an asteroid field while managing **fuel, health, and limited turns**.

The goal is to **maximize the score within 10 turns** by choosing between safe mining, aggressive mining, or refueling.

---

# 🎮 Game Overview

In **Space Miner**, the player explores an asteroid field to collect minerals.
Each action has risks and rewards.

You must decide whether to:

* Mine safely for small but reliable rewards
* Mine aggressively for higher rewards but higher risk
* Refuel to continue mining

The game ends after **10 turns**, and the final score is displayed.

---

# 🕹️ Controls

| Key              | Action            |
| ---------------- | ----------------- |
| **1**            | Safe Mining       |
| **2**            | Aggressive Mining |
| **3**            | Refuel            |
| **Close Window** | Exit Game         |

---

# ⚙️ Game Mechanics

### ⛏️ Safe Mining

* **80% chance** → +5 minerals
* **20% chance** → nothing found
* Fuel becomes **Low**

### ⚡ Aggressive Mining

* **50% chance** → +12 minerals
* **30% chance** → +5 minerals
* **20% chance** → ship damage and **-8 score**

### ⛽ Refuel

* Restores fuel to **High**
* Costs **1 score**

---

# 🧠 Strategy

To achieve the highest score:

* Use **safe mining early** to build steady points
* Use **aggressive mining when fuel is available**
* Refuel only when necessary
* Avoid too many aggressive attempts that could damage the ship

---

# 📊 Game Interface

The screen is divided into **three sections**:

### 🚀 Ship Area

Displays the player’s spaceship.

### ☄️ Asteroid Field

Shows the asteroid mining zone.

### 📈 Score Panel

Displays:

* Current **Score**
* Ship **Health**
* **Turns Remaining**

Additionally, a **fuel bar** indicates whether fuel is **High or Low**.

---

# 🧱 Technologies Used

* **Python**
* **Pygame** for game development
* Randomized events using Python’s `random` module

---

# ▶️ How to Run the Game

### 1️⃣ Install Pygame

```bash
pip install pygame
```

### 2️⃣ Run the Game

```bash
python space_miner.py
```

---

# 🎯 Game Objective

Maximize your **mineral score before the 10 turns end**.

Your final score will appear when the game ends.

---

# 📌 Possible Future Improvements

* 🚀 Moving spaceship animations
* ☄️ Random asteroid movement
* 🔊 Sound effects
* 💥 Damage animations
* 🎮 Mouse-based controls
* 📊 High score system

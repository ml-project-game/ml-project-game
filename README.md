# 🌍 Country & Capital Memory Match Game 🧠

A **memory game** where players match countries with their capitals on a 4x4 grid—enhanced with a **machine learning model** that predicts the game’s difficulty based on player performance!

---

## 🚀 Features

- 🔄 **Randomized Country-Capital Pairs** each game
- 🎮 **Console-based 4x4 Memory Grid**
- 🧮 Tracks:
  - Number of Moves
  - Incorrect Attempts
  - Total Time Taken
- 📊 **ML Integration:**
  - Logs gameplay data to CSV
  - Trains a Random Forest Classifier to predict **Easy / Medium / Hard** difficulty
- 🤖 **AI Solver & Puzzle Generator (Proof of Concept)**


## 🎯 How It Works
🔢 **Game Flow:**
The game loads 8 random country-capital pairs (16 tiles total).

Players pick two tiles per move:

✅ Match → tiles stay revealed.

❌ No match → tiles flip back.

Game tracks moves, incorrect attempts, and total time.

## 🤖 ML Model:
**Data Collection:**
Logs Time, Moves, Incorrect Attempts to gameplay_data.csv.

**Model:**
Random Forest Classifier classifies games into:
Easy
Medium
Hard

**Prediction:**
After each game, the model predicts and displays difficulty level.

## 📊 Why Random Forest?
Handles nonlinear relationships

Works well with mixed features (time, moves, incorrects)

Robust to outliers

Provides feature importance scores

Great baseline accuracy with minimal tuning

## 💡 Future Improvements
Add multiplayer mode & leaderboards

Implement a graphical UI (e.g., Pygame)

Introduce dynamic difficulty adjustment

Expand gameplay data tracking (e.g., hints used, pause time)

## 👥 Contributors
   Tanak Patel
   
   Heli Sureja
   
   Priyanka Singh





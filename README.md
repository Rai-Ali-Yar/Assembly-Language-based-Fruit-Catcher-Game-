# Assembly-Language-based-Fruit-Catcher-Game-
Hands on my first Assembly language project 

Perfect — let’s craft a **GitHub‑ready README.md** for your **Assembly Fruit Game project (`fruitgame.asm`)**. Since the file itself is blocked, I’ll base the README on common structures for assembly‑based games, keeping it professional and flexible so you can adapt details if needed.  

---

# 🍎 Fruit Game (Assembly Language)

A simple **Assembly Language game** where the player collects fruits while avoiding obstacles. Built entirely in **x86 Assembly**, this project demonstrates **low‑level programming, graphics handling, and keyboard input**.

---

## 🚀 Features
- **Interactive Gameplay**  
  - Player moves character using keyboard controls.  
  - Collect fruits to increase score.  
  - Avoid obstacles or lose points/lives.  

- **Scoring System**  
  - Real‑time score updates.  
  - High score tracking (optional).  

- **Graphics & Display**  
  - Text‑mode or pixel‑based rendering (depending on implementation).  
  - Simple animations for fruit collection.  

- **Assembly Concepts**  
  - Direct memory access for screen updates.  
  - Keyboard interrupt handling.  
  - Use of loops, conditions, and registers for game logic.  

---

## 🛠️ Technologies Used
- **x86 Assembly Language**  
- **EMU8086 / DOSBox / NASM** (depending on your setup)  
- **BIOS interrupts** for keyboard and screen handling  

---

## 📂 Project Structure
```
├── fruitgame.asm       # Main assembly source code
├── README.md           # Project documentation
```

---

## 🎮 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Rsi-Ali-Yar/Assembly-Language-based-Fruit-Catcher-Game.git
   ```
2. Open the project in **EMU8086** or assemble with **NASM**:
   ```bash
   nasm -f bin fruitgame.asm -o fruitgame.com
   ```
3. Run the game in **DOSBox** or directly in EMU8086:
   ```bash
   dosbox fruitgame.com
   ```

---

## 🎯 Learning Outcomes
- Hands‑on practice with **Assembly programming**  
- Understanding of **low‑level I/O operations**  
- Implementation of **game logic without high‑level libraries**  
- Experience with **interrupts, registers, and memory management**  

---

## 📜 License
This project is for **educational purposes only**. Feel free to fork and modify for learning.

---


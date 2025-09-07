# Candy Crush Game in Assembly

# 📌 Overview

This project is a simplified version of Candy Crush, developed in x86 Assembly language. The game implements a grid-based system where players can match candies, score points, and experience basic gameplay mechanics. It demonstrates low-level programming skills, graphics handling, and logic design.

# ⚙️ Requirements

 - DOSBox (to emulate DOS environment)

 - TASM / MASM assembler (to compile candy.asm)

🚀 How to Run

1. Install and open DOSBox.

2. Mount the directory containing candy.asm.

  mount c C:\path\to\your\project
  c:


3. Assemble the file:

  tasm candy.asm
  tlink candy.obj


4. Run the game:

  candy.exe

# 🎮 Features

 - Grid-based candy placement

 - Matching mechanism for points

 - Score tracking system

 - Basic UI using Assembly graphics

# 📂 File Structure

candy.asm → Source code of the game

# 📖 Notes

Designed for educational purposes to explore Assembly programming and low-level game development.

Tested on DOSBox with TASM.

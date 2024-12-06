# AI Flappy Bird Game

This project is a Python implementation of the classic *Flappy Bird* game, enhanced with AI capabilities using the NEAT (NeuroEvolution of Augmenting Topologies) library. The AI learns to play the game by training a population of neural networks to control the bird's actions.

## Features

- **Classic Flappy Bird Gameplay:** The game includes familiar mechanics like pipes, a bird with smooth animations, and a moving base.
- **AI-Powered Bird:** The bird is controlled by an AI that learns to navigate through pipes using neural networks.
- **NEAT Implementation:** Uses the NEAT-Python library to evolve the AI's neural networks over multiple generations.
- **Fitness-Based Evolution:** The AI's fitness increases as it survives longer and successfully passes pipes.

---

## Table of Contents

1. [Screenshots](#screenshots)
2. [Requirements](#requirements)
3. [How to Run](#how-to-run)


---

## Screenshots

![image](https://github.com/user-attachments/assets/09b8c69b-f78f-4393-8b0e-b9d0f889efea)


---

## Requirements

- Python 3.7 or higher
- Libraries:
  - `pygame`
  - `neat-python`

Install the required dependencies using:

```bash
pip install pygame neat-python
```

## How to Run
```bash
python flappy_game.py
```

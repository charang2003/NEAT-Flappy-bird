# NEAT Flappy Bird

This project implements a Flappy Bird clone using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm for AI-driven gameplay. The game allows users to experience the classic Flappy Bird mechanics while showcasing the capabilities of neuroevolution in training AI agents. Players control a bird navigating through pipes, with the goal of achieving the highest score possible. The project demonstrates the integration of Pygame for game development and NEAT-Python for evolving intelligent agents.

## Table of Contents

1. [Introduction](#introduction)
2. [Gameplay](#gameplay)
3. [Game Components](#game-components)
4. [Features](#features)
5. [Installation](#installation)
6. [Usage](#usage)
7. [How It Works](#how-it-works)
8. [Configuration](#configuration)
9. [Contributing](#contributing)
10. [Creadits](#creadits)
11. [Acknowledgments](#acknowledgments)

## Introduction

The NEAT Flappy Bird project implements a neural network approach to train agents to play the classic Flappy Bird game using the **NEAT** (NeuroEvolution of Augmenting Topologies) algorithm. This project demonstrates the application of evolutionary algorithms in game AI, allowing the birds to learn and adapt to the game environment.

## Gameplay

![Flappy Bird](path_to_your_gif.gif)

## Game Components

- **Snake**: ![Snake](path/to/snake_image.png)
- **Food**: ![Food](path/to/food_image.png)
- **Score**: ![Score](path/to/score_image.png)

## Features

- Playable Flappy Bird game using Pygame.
- NEAT algorithm for training neural networks.
- Visual representation of birds and their evolution.
- Real-time scoring and performance tracking.

## Installation

Follow these steps to set up and run the project on your local machine.

### Prerequisites

Make sure you have the following installed:

- **Python 3.x**
- **pip** (Python package installer)
- **PyGame**
- **PyTorch**

### Steps

1. **Clone the Repository:**

   Clone this repository to your local machine:

   ```bash
   git clone https://github.com/charang2003/NEAT-Flappy-bird.git
   cd NEAT-Flappy-bird

   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To train the AI agent and watch it play Snake game:

```bash
python flappy_bird.py
```

## How It Works

The project uses Pygame for rendering the game and NEAT for evolving a population of birds. Each bird is represented by a neural network that makes decisions based on its position relative to the pipes. The birds are trained over multiple generations, improving their performance with each iteration.

### Key Components

- **Bird Class:**
  Handles bird movement, drawing, and collision detection.
- **Pipe Class:**
  Manages the creation, movement, and collision of pipes.

- **Base Class:**
  Draws and moves the ground in the game.

- **NEAT Configuration:**
  Defines the structure and parameters for the NEAT algorithm.

## Configuration

Before running the project, you'll need to configure the config-feedforward.txt file. This file contains the settings for the NEAT algorithm. Customize parameters such as:

- **Population Size:**
  Determines how many genomes will be evaluated in each generation.
- **Fitness Evaluation:**
  Set how the fitness of each bird is calculated.

- **Neural Network Architecture:**
  Adjust the number of inputs, hidden layers, and outputs based on your requirements.

Feel free to explore the various configurations and experiment with different settings to see how they affect the performance of your neural networks!

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## Creadits

This project was inspired by `NeuroEvolution of Augmenting Topologies (NEAT)` a genetic algorithm (GA) developed by Kenneth Stanley and Risto Miikkulainen in 2002. Special thanks to the following resources that contributed to the development of this project:

- **NEAT-Python:**
  The implementation of the NEAT algorithm used for neuroevolution.
- **Pygame:**
  The library used for creating the game environment.

- **Flappy Bird:**
  Inspiration for the project, showcasing the mechanics of the original game.

And special thanks to Tech with Tim -->
[Watch the Video](https://youtu.be/MMxFDaIOHsE?si=TzMnwLxHDMjV7E6J)

## Acknowledgments

- `Pygame` for the game development library.
- `NEAT` for the neuroevolution algorithm.
- Inspiration from the original Flappy Bird game.

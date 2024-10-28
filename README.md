# **Flappy Bird NEAT AI**

This is an AI-powered Flappy Bird game built using Python and Pygame, with an evolutionary algorithm based on NEAT (NeuroEvolution of Augmenting Topologies) to train the birds to play the game autonomously. Each bird (or agent) learns to avoid pipes and survive as long as possible, improving its performance over generations.


**Table of Contents**

•  [Overview](#overview)

•  [Features](#features)

•  [Installation](#installation)

•  [Usage](#usage)

•  [License](#license)

**Overview**

The project uses the NEAT Python library to implement a genetic algorithm for neural networks. The AI birds (agents) evolve over generations, optimizing their neural networks based on their ability to navigate through pipes and avoid collisions. NEAT handles the evolving and mutation of these networks, allowing birds to learn from previous generations.

**Features**

•  **Neuroevolution**: Birds learn to play Flappy Bird using the NEAT algorithm, which evolves the neural network weights and structures.

•  **Automatic Restart**: The game restarts with new generations of birds as they evolve their ability to avoid pipes.

•  **Graphical Display**: Visualizes the game using Pygame and displays scores on-screen.

**Installation**

1. **Clone this repository**:

```bash
git clone https://github.com/yourusername/flappy-bird-neat-ai.git
cd flappy-bird-neat-ai
```
3. **Directory Structure**:

Place all necessary images (such as bird1.png, bird2.png, bird3.png, pipe.png, base.png, and bg.png) in an imgs folder within your project directory.

**Usage**

1. **Configure NEAT**: Customize the NEAT configuration file (config-feedforward.txt) to adjust population size, mutation rates, and other NEAT settings.

2. **Run the game**:
```bash
python flappy_bird_neat.py
```
The NEAT algorithm will automatically begin training, and you can observe the birds as they learn to navigate through the pipes. The score increases as birds successfully avoid pipes.

**License**

This project is licensed under the MIT License. Feel free to use and modify as needed.

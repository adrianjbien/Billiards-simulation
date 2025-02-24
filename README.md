# Billiards Simulation
This project is a billiards simulation developed in C#, featuring concurrent processing to enhance performance and realism. The simulation models billiard ball interactions, trajectories, and dynamics in a virtual environment.

## Overview
The simulation accurately represents the physics of billiards, using multithreading and concurrency to efficiently compute collisions, friction, and movement. This approach ensures smooth performance, even when multiple balls are in motion simultaneously.

## Features
Physics Modeling: Accurate simulation of ball movement, collisions, and friction.

Concurrent Processing: Utilizes multithreading to handle multiple moving balls efficiently.

Modular Design: Organized into distinct components for data management, game logic, and UI.

Extensibility: Easily adaptable for additional features or game variations.

## Project Structure

### The repository follows the MVVM (Model-View-ViewModel) architecture, structured as follows:

Model/: Contains the core billiards physics and data models.

View/: Implements the graphical user interface using WPF.

ViewModel/: Acts as an intermediary between the View and Model, managing UI interactions, commands, and data binding.

Logika/: Contains the game logic and physics calculations, optimized with concurrent processing.

Dane/: Manages data storage and persistence.

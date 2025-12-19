# Unity Car AI

This is a Unity project that uses a genetic algorithm to train an AI to drive a car around a track.

## Description

The project consists of a simple car controller, a sensor system that uses raycasts to detect the environment, and a genetic algorithm that trains the car to navigate the track.

The AI's "brain" is a polynomial regression model. The genetic algorithm evolves the coefficients of this model to find the optimal driving behavior. The fitness of each "genome" (set of coefficients) is determined by how far the car travels on the track without crashing.

## Features

*   **Genetic Algorithm:** The core of the project is a genetic algorithm that trains the car's AI.
*   **Polynomial Regression:** The AI uses a polynomial regression model to decide its actions based on sensor input.
*   **Raycast Sensors:** The car is equipped with a set of raycast sensors to perceive its environment.
*   **Modular Track:** The project includes a modular track that can be easily modified or extended.
*   **Data Logging:** The `Sensors.cs` script includes a feature to log sensor data and user input to a file, which can be used for offline training or analysis.

## How to Run

1.  Clone this repository.
2.  Open the project in Unity Hub.
3.  Open the `Assets/JuanScene.unity` scene.
4.  Press the "Play" button in the Unity editor.

The genetic algorithm will then start, and you will see the cars learning to drive around the track.

This project is built using Unity.

## License

This project does not have a license. You are free to use it as you wish.

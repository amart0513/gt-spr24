# Game Theory Automation Project

## Overview

This project aims to automate various aspects of game theory research and analysis using Java programming language. Game theory deals with mathematical models of strategic interactions between rational decision-makers. The project aims to provide tools and algorithms to streamline the process of studying and analyzing games, facilitating both theoretical research and practical applications in various domains such as economics, political science, biology, and computer science.

## Features

- **Game Representation**: Provides classes and interfaces for representing various types of games, including normal-form games, extensive-form games, and cooperative games.
- **Solution Concepts**: Implements algorithms for computing solution concepts such as Nash equilibrium, subgame-perfect equilibrium, correlated equilibrium, and others.
- **Game Analysis**: Offers tools for analyzing games, including dominance analysis, equilibrium refinement, and sensitivity analysis.
- **Simulation**: Allows for simulating game outcomes under different strategies and scenarios, facilitating empirical analysis and experimentation.
- **Visualization**: Provides utilities for visualizing games graphically and analyzing the outcomes visually.
- **Integration**: Supports integration with existing Java libraries and frameworks, allowing for interoperability and extending functionality.

## Installation

1. Clone the repository:
    
    git clone https://github.com/your_username/game-theory-automation-java.git
    

2. Navigate to the project directory:

    cd game-theory-automation-java


3. Set up the project in your preferred Java development environment.

## Usage

1. Import the necessary packages:

import com.yourpackage.gameTheory.*;
// Example: Create a normal-form game
NormalFormGame game = new NormalFormGame(new String[]{"Player 1", "Player 2"},
                                         new String[][]{{"A", "B"}, {"C", "D"}},
                                         new double[][]{{3, 1}, {2, 4}, {0, 0}, {1, 2}});

// Example: Compute Nash equilibrium
double[][] nashEq = game.computeNashEquilibrium();

// Example: Visualize the game
game.visualize();



## Contributions

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your_feature).
3. Make your changes.
4. Commit your changes (git commit -am 'Add new feature').
5. Push to the branch (git push origin feature/your_feature).
6. Create a new Pull Request.
7. Please ensure that your pull request adheres to the project's coding standards and guidelines.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or feedback, please contact amart1070@fiu.edu.



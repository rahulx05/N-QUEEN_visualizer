# N-Queens Visualizer

Welcome to the N-Queens Visualizer! This project provides a visual representation of the N-Queens problem, allowing users to understand and explore different solutions for various board sizes.

## Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Contact](#contact)

## Overview

The N-Queens problem is a classic puzzle where the goal is to place N queens on an N×N chessboard such that no two queens threaten each other. This visualizer allows users to input the number of queens, adjust the speed of the visualization, and see the possible arrangements.

## Problem Statement

The N-Queens problem involves placing N chess queens on an N×N chessboard so that no two queens can attack each other. This means:

- No two queens can be in the same row.
- No two queens can be in the same column.
- No two queens can be on the same diagonal.

The challenge is to find all possible arrangements where these conditions are met.

## Features

- **Input Handling:** Allows users to input the number of queens (N) they want to visualize.
- **Speed Control:** Users can adjust the speed of the visualization using a slider.
- **Play Button:** Starts the visualization of the N-Queens problem.
- **Dynamic Board:** Displays the chessboard and places queens on it according to the solution.
- **Responsive Design:** Adapts to different screen sizes for better user experience.

## Technologies Used

- **HTML:** For structuring the web page.
- **CSS:** For styling the web page.
- **JavaScript:** For the logic and functionality of the visualizer.
- **FontAwesome:** For icons used in the project.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/rahulx05/n-queens-visualizer.git
    ```

2. Navigate to the project directory:

    ```bash
    cd n-queens-visualizer
    ```

3. Open `index.html` in your web browser to run the visualizer.

## Usage

1. Open the visualizer in your browser.
2. Enter the number of queens (N) in the input box.
3. Adjust the speed of the visualization using the slider.
4. Click the "Play" button to start the visualization.
5. Watch as the board populates with queens in non-threatening positions.

## Code Explanation

### HTML (index.html)

The HTML file structures the web page, including the header, input box, slider, and buttons. It links to the CSS and JavaScript files for styling and functionality.

### CSS (style.css)

The CSS file styles the web page, ensuring a visually appealing and user-friendly interface. It includes styles for the header, input box, slider, play button, and the chessboard.

### JavaScript (app.js)

The JavaScript file contains the logic for the N-Queens visualization. It includes:

- Handling user inputs for the number of queens and the speed of visualization.
- Defining the `Queen` class with methods to solve the N-Queens problem.
- Updating the chessboard dynamically to show the placement of queens.

## Contact

For any questions or feedback, please contact:

- **Name:** Rahul
- **GitHub:** [rahulx05](https://github.com/rahulx05)
- **Email:** [rbpanchal511@gmail.com]

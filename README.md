# ECW
Constant Point in an Ever Changing World (ECW): https://interstellar-hitchhiker.github.io/ECW/

This project visualizes the concept of a constant spatial point in an ever-changing world, using a dynamic animation created with p5.js. The visualization illustrates a fixed point, represented by the symbol "X," which remains constant while time progresses and particles move around it like Pong balls, symbolizing the flux and movement in the surrounding environment.
Purpose

The purpose of this project is to create a visual representation of constancy amidst change. It highlights how certain points or elements remain unchanged over time while everything around them is in constant motion. This concept is often seen in various philosophical, scientific, and mathematical contexts.
Features

    Fixed Point Visualization: A constant point represented by "X" stays at the center of the canvas, illustrating constancy.
    Dynamic Particles: Particles move and bounce around the canvas, symbolizing change and movement.
    Time Progression: The time coordinate t increases every second, indicating the passage of time.
    Mathematical Explanation: An explanation of the visualization and its mathematical basis is provided below the canvas.

Usage

    Clone the Repository:

    bash

    git clone https://github.com/yourusername/ECW.git
    cd constant-point

    Open index.html in a Browser:
    Simply open the index.html file in any modern web browser to see the visualization in action.

Code Explanation
HTML and CSS

The HTML file defines the structure of the web page, including the canvas for the visualization, a header, and an explanation section. The CSS styles the page, providing a dark theme and a clean, modern look.
JavaScript with p5.js

The JavaScript code uses the p5.js library to create and animate the visualization.
Key Components

    Fixed Point:
        Represented by a, b, and c coordinates, with initial values (0, 0, 0).
        The symbol "X" is displayed at this fixed point, and its coordinates with the time t are shown.
    Particles:
        An array of Particle objects is created, each with random initial positions and velocities.
        The update method moves the particles, making them bounce off the edges of the canvas.
    Time Progression:
        A setInterval function updates the time t every second, which is then displayed alongside the fixed point.

Functions

    setup(): Initializes the canvas, sets the interval for time updates, and creates the particles.
    draw(): Continuously updates the canvas, moves the particles, and draws the fixed point and its coordinates.
    drawConstantPoint(x, y): Draws the fixed point and its coordinates on the canvas.
    updateTime(): Increments the time t and triggers a canvas redraw.
    Particle: A class defining the properties and behaviors of the moving particles, including their update and show methods.

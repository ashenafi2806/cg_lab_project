3D Solar System Simulation
A 3D solar system built with C++ and OpenGL (GLUT). Watch planets orbit the Sun, Earth's moon spin, and take control with slick camera moves.

Features
Full planet: Sun, Mercury, Venus, Earth (+Moon), Mars, Jupiter, Saturn, Uranus, Neptune
Custom sizes, colors, and orbit distances for that real-space vibe
Mouse drag to rotate, scroll to zoom
Clean gray orbit paths for each planet
How It's Built
Planets: Rendered with glutSolidSphere
Orbits: Drawn using GL_LINE_LOOP
Smooth animation using GLUT timer
Description: We started by drawing spheres for each planet and updated their position using basic trigonometry.
We added orbits using line loops and used timer functions for smooth animation.
For the 3D view, we added camera controls and zoom functionality.

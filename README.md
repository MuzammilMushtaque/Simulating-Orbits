# Orbital Dynamics Simulator

This GitHub repository provides a comprehensive simulation of orbits in various gravitational scenarios, covering fundamental concepts such as spherical mass distributions, gravitational potentials of disks, and orbits in barred galaxies.

## Fundamentals of Orbits in Spherical Mass Distribution

The simulator begins by exploring the basics of orbits influenced by a spherical mass distribution. Key concepts include:

- **Spherical Mass Distribution:** Describing the gravitational force exerted by a spherically symmetric mass distribution on a particle.
  
- **Orbital Trajectories:** Computed using Newton's second law, where the gravitational field, mass of the body, and acceleration vector collectively define the trajectory.

- **Numerical Solving:** Utilizing numerical methods like the Euler Method or Runge-Kutta 4th order to solve second-order differential equations, determining the orbits based on initial phase-space coordinates.

- **Mass Considerations:** The test-particle's mass is negligible, ensuring it doesn't significantly impact the central gravitational field's evolution.

- **Keplerian, Spherical Harmonic, and Isochrone Potentials:** Initial attempts focus on testing orbits using these potentials for the first 6 planets of the Solar system. Calculations include total energy and distances.

## Gravitational Potential of Disks and Their Orbits

Building upon the basics, the simulator extends its scope to different potentials commonly used in defining galaxies:

1. **Razor-thin Disk: The Kuzmin Model**
2. **Thickened Disk: Miyamoto Nagai Model**
3. **Logarithmic Potential:** Introducing a constant circular velocity parameter to account for flat rotation curves observed in galaxies.

## Orbits in Barred Galaxies

The simulator further delves into the dynamics of orbits in barred galaxies, providing insights into the properties of bars, their extension, and pattern velocity. Key considerations include:

- **Triaxial Ellipsoids:** Modeling bars as three-dimensional components, considering their thickness due to vertical resonances.
  
- **Axisymmetric Potential:** Describing the characteristics of orbits in the plane z = 0 within an axisymmetric potential.

- **Bisymmetric Gravitational Potential:** Created by the bar, rotating in the galaxy with the pattern speed b.

- **Final Potential:** Combining the logarithmic potential, bar potential, and centrifugal potential to account for the rotating frame.

Understanding stellar orbits in barred galaxies enhances our knowledge of dynamical properties, extensions, and resonances within these complex galactic structures.

Feel free to explore the provided Python scripts to gain insights into these fascinating gravitational scenarios. Your feedback and contributions are welcome!
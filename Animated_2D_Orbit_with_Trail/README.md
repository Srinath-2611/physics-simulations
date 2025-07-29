# 🌍 Planetary Orbit Simulation with Animation (2D)

This project simulates the circular orbit of a planet around a star (like the Sun) using basic Newtonian gravity. It also includes a **matplotlib animation** to visually demonstrate the orbital motion with a trailing path.

## ✨ Features
- Simulates a planet in a 2D circular orbit using classical mechanics.
- Includes a real-time animation with the planet, Sun, and orbital trail.
- Configurable parameters like timestep and number of steps.
- Written entirely in Python using `matplotlib` and `numpy`.

## 🔭 Physics Background
This simulation is based on Newtonian gravitational force:
$ F = \frac{G M m}{r^2}$
The resulting acceleration is used to update the planet’s velocity and position via the Euler method.

Though simplified, it serves as a great starting point for:
- Visualizing planetary motion
- Understanding gravitational force and orbital dynamics
- Extending to elliptical orbits or multiple bodies

## 🛠️ Technologies Used
- Python 3
- `matplotlib` (for plotting and animation)
- `numpy` (for numerical arrays and calculations)

## 📸 Demo
![Orbit Screenshot](Animated_2D_Orbit_with_Trail/Animated 2D Orbit with Trail.png)  
_(Replace this with your actual screenshot or GIF if uploaded)_

## ⚙️ Parameters
You can tweak the following for experimentation:
- `dt` — Timestep (seconds)
- `num_steps` — Number of steps in the simulation
- Initial velocity and radius — Controls the shape of orbit

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/planetary-orbit-simulation.git

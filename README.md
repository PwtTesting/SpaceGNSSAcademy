Satellite Orbit Explorer 🛰️
Orbital propagation, ground-track analysis and visualization with Python
GNSS Academy — Space Career Week 2026

Overview
This educational project explores how orbital elements can be transformed into satellite trajectories, ground tracks and velocity profiles. It was developed during GNSS Academy's Space Career Week 2026, using a Python notebook in Google Colab.

The emphasis is on understanding the underlying physics, reviewing the implementation and checking whether the numerical and visual outputs are physically consistent.
What the notebook does
1. Loads General Perturbations (GP) orbital-element records in JSON format from a workshop snapshot.
2. Extracts the orbital elements and creates a common 24-hour UTC simulation window.
3. Propagates the orbits with a two-body Keplerian approximation, solving Kepler's equation numerically.
4. Converts inertial positions to Earth-fixed coordinates using a Greenwich sidereal-time approximation and a spherical-Earth model.
5. Calculates orbital periods, perigee/apogee altitudes and orbital-speed ranges.
6. Produces ground-track and speed-versus-time plots with Matplotlib.
7. Exports 3D orbit paths and timestamped ground-track animations as KML for Google Earth Pro, plus a text report.
8. Optionally retrieves updated GP data from CelesTrak, with a two-hour local cache to avoid unnecessary requests.

Development and acknowledgments
This project was completed as part of a GNSS Academy Space Career Week 2026 workshop. The Python implementation was developed with AI assistance (Gemini). My focus was on interpreting the workshop requirements, reviewing and debugging the code, understanding the orbital mechanics, and checking the numerical and visual results using an engineering Verification & Validation mindset.

Orbital data: CelesTrak. Workshop concept and learning material: GNSS Academy.

Author: Marco Testa
Topics: Python · Orbital Mechanics · Satellite Ground Tracks · Data Visualization · Systems Engineering · Verification & Validation

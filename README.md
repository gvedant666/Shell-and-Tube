
---

## **Shell & Tube Heat Exchanger Python Project**

```markdown
# Shell & Tube Heat Exchanger Design Calculator

## Overview
This Python project calculates the **design parameters of a Shell & Tube Heat Exchanger** for a given hot and cold fluid. It determines flow rates, heat transfer coefficients, pressure drops, LMTD correction factors, and iteratively refines the overall heat transfer coefficient (U). The tool helps optimize heat exchanger design for efficiency and cost-effectiveness.

## Features
- Calculates caloric temperatures and properties of hot (Heavy Naphtha) and cold (Water) fluids
- Determines **mass flow rates**, **heat transfer area**, and **number of tubes** required
- Computes **Reynolds number**, **Nusselt number**, and heat transfer coefficients for tube and shell sides
- Evaluates **pressure drop** and overdesign percentage
- Incorporates **LMTD and correction factors** for different configurations (1-2 or 2-4 passes)
- Iterative calculation for accurate **overall heat transfer coefficient (U)**

## Tech Stack / Tools Used
- Language: Python 3
- Libraries: NumPy, Matplotlib
- Engineering concepts: Heat transfer, thermodynamics, fluid mechanics

## Usage
1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Input the hot and cold fluid parameters, temperatures, and mass flow rates when prompted.
3. The program calculates and prints:
   - Caloric temperatures and fluid properties
   - Heat transfer area and tube requirements
   - Tube and shell side Reynolds numbers and heat transfer coefficients
   - LMTD and correction factors
   - Pressure drop and overdesign evaluation

## Learning / Takeaways
- Practical application of **thermodynamics and heat transfer principles**
- Python implementation of **engineering calculations** with iterative refinement
- Fluid property interpolation and empirical correlations for heat exchanger design

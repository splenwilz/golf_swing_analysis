
# Biomechanical Analysis of Human Movement with Pyomeca and Biorbd

This project demonstrates how to perform a biomechanical analysis of human movement using Pyomeca and Biorbd. The analysis focuses on the kinematics and kinetics of a golf swing motion captured using motion capture data.

## Overview

The project involves the following steps:

1. Importing required libraries
2. Loading motion capture data
3. Processing the data using Pyomeca
4. Creating a musculoskeletal model of the human body using Biorbd
5. Calculating muscle forces, joint torques, and power output using Biorbd
6. Formulating the problem as an optimal control problem
7. Solving the optimal control problem using CasADi
8. Visualizing the results

## Requirements
- Anaconda or Miniconda
- Python 3.7 or later
- Pyomeca
- Biorbd
- CasADi
- Matplotlib

## Usage

1. Clone the repository:

`git clone https://github.com/splenwilz/golf_swing_analysis.git`


2. Install the required dependencies:

`conda install -c conda-forge pyomeca`
`conda install -c conda-forge biorbd`

3. Run the analysis:

python golfAnalysis.py

4. View the results:

The results will be saved in the `results` folder. Use the following command to view the results:

python visualize_results.py


## Acknowledgements

The motion capture data used in this project was obtained from the Carnegie Mellon University Motion Capture Database.




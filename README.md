
## Hopfield Networks as Energy-Based Models: Theory, Implementation, and Evaluation

This repository contains the code, experiments, and accompanying tutorial for a study of Hopfield Networks within the framework of Energy-Based Models (EBMs). The project demonstrates how associative memory, attractor dynamics, and energy minimisation arise from the structure of the Hopfield energy function. All experiments are implemented in Python using NumPy and visualised through Matplotlib.

The tutorial includes explanations of the Hopfield architecture, Hebbian learning, memory recall dynamics, evaluation of memory capacity, and analysis of energy landscapes. Synthetic binary patterns are used to illustrate storage, noise tolerance, and convergence behaviour. The results provide an interpretable example of energy-based computation and its limitations.

Repository Structure
├── tutorial.pdf                # Final written tutorial (<2000 words)
├── Rajesh_ML_Code.ipynb        # Jupyter notebook with all code and plots
├── figures/                    # Stored, noisy, reconstructed, energy, capacity plots
├── README.md                   # Project documentation
├── LICENSE                     # Usage license (MIT recommended)

## Requirements

Python 3.8+

NumPy

Matplotlib

Jupyter Notebook or JupyterLab

Install dependencies with:

pip install numpy matplotlib

## Running the Notebook

To reproduce the experiments:

Clone the repository

Open Rajesh_ML_Code.ipynb in Jupyter

Run all cells to generate the figures used in the tutorial

All output plots—including energy descent, capacity curve, and pattern reconstructions—will be recreated automatically.

## Dataset

The notebook generates synthetic 
8
×
8
8×8 binary patterns for training and evaluation. No external dataset is required.

License

This project is released under the MIT License.
You may use, modify, and distribute the code with attribution.

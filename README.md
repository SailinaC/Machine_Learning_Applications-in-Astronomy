# Machine Learning for Physics and Astronomy

This repository contains notebooks and exercises exploring machine learning methods in physics and astronomy, with a strong focus on Bayesian inference. It includes both lecture exercises and a project on modeling the expansion of the universe.

## Repository Structure

    machinelearning4physics_bicocca_2025_solutions/
    ├── lectures/                       # Lecture exercises
    │   ├── datasets/                   # Datasets used
    │   ├── MontyHall.ipynb             # -> Probability theory
    │   ├── BlackHoles.ipynb            # -> Sampling
    │   ├── Exoplanets.ipynb            # -> Density estimation
    │   ├── WeatherNDimBalls.ipynb      # -> Markov chains
    │   ├── TimeTransients.ipynb        # -> MCMC
    │   ├── HiggsBoson.ipynb            # -> Model selection
    │   └── NestedSampling.ipynb        # -> Nested sampling
    ├── project/                        # Project exam
    │   ├── data/                       # Supernovae data
    │   └── UniverseExpansion.ipynb     # Project file
    └── README.md                       # Documentation

## Key Topics Covered
- Probability Theory: Monty Hall problem, Bayesian reasoning
- Sampling Methods: Black holes example, Monte Carlo sampling
- Density Estimation: Exoplanet data analysis
- Markov Chains & MCMC: Weather simulation and transient events
- Model Selection & Bayesian Evidence: Higgs boson and nested sampling examples
- Practical Projects: Universe expansion modeling using real supernovae data

## Requirements
- Python ≥ 3.10
- Jupyter notebook
- Libraries: `arviz`, `corner`, `dynesty`, `matplotlib`, `numpy`, `pandas`, `pymc`, `pytensor`, `scipy`, `seaborn`, `scikit-learn`

You can install the required packages via:

    pip install -r requirements.txt

## Usage
1. Clone the repository

        git clone https://github.com/YiMingPan-Xv/ml4astronomy.git

2. Navigate to the repository

        cd ml4astronomy

3. Launch Jupyter Notebook and open any notebook from the `lectures/` or `project/` folder:

        jupyter notebook

# Warehouse Optimizer

This algorithm simulates a warehouse with various locations, shelves, and bins on the shelves. The products are simulated based on a pareto 80/20 rule. An initial random position of the products is simulated and analyzed. Then the products are moved to optimize their relative positions and the picking distance. 

## Code Setup

I use the [Anaconda Python 3.7 distribution](https://www.anaconda.com/distribution/) with a virtual environment created from the `environment.yml` file. The environment is built from the root directory: `conda env create -f environment.yml`.

## Running Notebooks

Activate the conda environment with `conda activate warehouse_optimizer`. Then the jupyter server is run from the root directory: `jupyter notebook`.

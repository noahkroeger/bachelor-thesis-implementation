# Bachelor-Thesis: Boolean Matrix Factorization in the context of federated learning

This is the repository for my bachelor thesis about boolean matrix factorization in the context of federated learning. This thesis deals with the application and optimization of an existing Boolean Matrix Factorization algorithm to a new domain — federated learning.

The first part of the thesis is going to alter the SOFA Algorithm of the "Biclustering and Boolean Matrix Factorization in Data Streams" paper by Stefan Neumann and Pauli Miettinen to apply it to the federated learning context.

## Repository structure

The repository contains the full C++ implementation for the thesis, as well as related code resources such as training scripts and the requirements.txt file.

## Installation

To install the implementation on your local device follow these steps.

First clone the repository into your local directory


git clone git@gitlab.com:username/thesis.git


Switch into the directory to execute the script.


cd thesis/code


Create a virtual environment and start it.


python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate   # Windows


Install the necessary dependencies from the requirements.txt file


pip install -r requirements.txt


## Usage

After installation you can execute the scripts to reproduce the experiment and compile the latex thesis.

### Run experiments

### Compile LaTeX thesis

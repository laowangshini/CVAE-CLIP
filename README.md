# CVAE-CLIP Project

## Overview
This project contains code for training and evaluating a Conditional Variational Autoencoder (CVAE) model on the CelebA dataset. The primary goal is to generate images conditioned on specific attributes using the CVAE model.

## Environment Setup and Dependencies
To set up the environment and install the required dependencies, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/laowangshini/CVAE-CLIP.git
   cd CVAE-CLIP
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Jupyter Notebooks
To run the Jupyter notebooks for training and testing the models, follow these steps:

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open the desired notebook (e.g., `clip_cvae_celeba_test4.ipynb` or `realtest2_cvae.ipynb`) and run the cells to train and evaluate the models.

## Repository Structure
The repository contains the following files and directories:

- `clip_cvae_celeba_test4.ipynb`: Jupyter notebook for testing the CVAE model on the CelebA dataset.
- `realtest2_cvae.ipynb`: Jupyter notebook for training and evaluating the CVAE model on the CelebA dataset.
- `.gitignore`: File to exclude certain files and directories from version control.
- `requirements.txt`: File containing the list of required Python libraries and their versions.

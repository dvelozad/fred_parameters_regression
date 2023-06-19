# FRED Parameters Prediction with ROCKET

This repository contains code for training a machine learning model using ROCKET and scikit-learn to predict the parameters of the FRED agent-based model. The FRED model simulates the spread of COVID and outputs various parameters related to the spread, including death reports.

## Repository Description

This repository contains the following directories and files:

- `input_files`: Contains input files required for the FRED simulation and the output files from the simulation, including `FRED_parameters_out.csv` and various data files related to different parameter variants.

- `scripts`: Contains Python scripts and Jupyter notebooks for data processing, loading functions, and training the ROCKET model to predict FRED parameters.

## Getting Started

To get started with this repository, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/your_username/fred-parameters-prediction.git
   ```

2. Install the required dependencies. The dependencies can be found in the `requirements.txt` file. You can install them using pip:

   ```
   pip install -r requirements.txt
   ```

3. Navigate to the `scripts/` directory and run the Jupyter notebooks or Python scripts to preprocess the data and train the ROCKET model.
## CNN-Transformer for Flame Nonlinear Response Reconstruction
## Overview
This repository contains the implementation of a deep learning model combining Convolutional Neural Networks (CNN) and Transformers to reconstruct the nonlinear response of flames from sequential data. The project addresses the problem of analyzing thermoacoustic instabilities by accurately predicting flame responses, which are crucial for designing safe and efficient combustion systems.

## Key Features
CNN-Transformer Hybrid Architecture: Utilizes the strengths of CNNs for feature extraction and Transformers for capturing long-range dependencies in time-series data.
Flame Response Prediction: Capable of reconstructing nonlinear flame responses from input perturbations across a range of frequencies and amplitudes.
Thermoacoustic Instability Analysis: Predicts combustion instability behaviors which are vital for aero-engine and gas turbine designs.
Project Structure
/models/: Contains the model architectures for CNN, Transformer, and hybrid CNN-Transformer.
/data/: Example input data of velocity disturbances and corresponding flame responses.
/notebooks/: Jupyter notebooks to demonstrate model training, evaluation, and visualization of results.
/results/: Model outputs and visualizations of flame response predictions compared with theoretical benchmarks.
Requirements
Python 3.x
PyTorch: Deep learning framework for implementing the models.
NumPy and Pandas: For data manipulation and preprocessing.
Matplotlib: For visualizing model performance and outputs.
Install the required packages using:

bash
Copy code
pip install -r requirements.txt
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/vida-lashani/CNN-Transformer-Flame-Response.git
Prepare the data: Place your input data of velocity disturbances in the /data/ directory. Make sure the data format follows the structure defined in the notebooks.

Train the model: Run the Jupyter notebook to train the CNN-Transformer model on the provided dataset.

bash
Copy code
jupyter notebook training_notebook.ipynb
Evaluate the model: After training, the model can be evaluated using a set of test signals to validate its predictive capabilities.

## Results
The model demonstrates high accuracy in reconstructing nonlinear flame responses from sequential input data, with minimal error when compared to theoretical models. This approach offers a scalable and computationally efficient alternative to traditional CFD simulations.

# **Variational Autoencoders (VAE) using Frey Face Dataset**
This repository contains code to implement Variational Autoencoders (VAE) using the Frey Face dataset and to sample points from the learned distribution by varying different latent variables to show that the network has learned meaningful latent variables.

## Requirements
To run the code in this repository, you need the following dependencies:

- Python (3.x)
- TensorFlow
- Keras
- NumPy
- Matplotlib
- scikit-learn

The code was developed and tested in Google Colab, which already provides most of the required libraries. However, if you are running the code in a different environment, make sure to install the dependencies before executing the notebook.

You can install the required packages using the following command:

**pip install tensorflow keras numpy scikit-learn matplotlib**

## Documentation
The main code implementation can be found in the notebook "DL_Assign3_Ques2.ipynb." This notebook contains the Python code to implement Variational Autoencoders, load the Frey Face dataset, train the VAE model, and sample points from the learned distribution by varying different latent variables. The notebook includes comments explaining each step of the code.

## Download Dataset
The Frey Face dataset is used for training and evaluation. To run the code, you need to download the dataset and ensure it is available in the "Freyface Dataset" directory. The dataset can be downloaded from the following link: Frey Face Dataset

## Directory Hierarchy
```
│   VAE
│   ├── src
│   │   ├── DL_Assign3_Ques2.ipynb
│   Data
│   ├── Freyface Dataset
```  
**src**: source codes of the VAE

The directory structure is organized as follows:

VAE: This is the root directory of the repository.
src: This subdirectory contains the main notebook "DL_Assign3_Ques2.ipynb" where the code for Variational Autoencoders is implemented.

Data: This subdirectory contains the downloaded Frey Face dataset.
Freyface Dataset: This subdirectory should contain the "frey_rawface.mat" file.

## Implementation Details
## Variational Autoencoders (VAE)

The implementation of Variational Autoencoders is done in Python using TensorFlow and Keras libraries. The code is provided in the "DL_Assign3_Ques2.ipynb" notebook.

## The steps include:

*  Importing the required libraries.
*  Loading and preprocessing the Frey Face dataset.
*  Defining and training the Variational Autoencoder model with an embedding vector size of 20.
*  Sampling points from the learned distribution by varying different latent variables.


## Results

The following results are obtained from the implementation:

## Loss Chart
The loss chart for the training and testing data during the training of the Variational Autoencoder is shown below. This chart provides insights into the training progress and convergence of the model.

## Sampled Images
Images generated by sampling points from the learned distribution by varying different latent variables are visualized to demonstrate that the network has learned meaningful latent variables.
The following results are obtained from the implementation:

## Running the Code
To run the code, follow these steps:

*  Open the Jupyter notebook "DL_Assign3_Ques2.ipynb" in Google Colab or any Python environment with the required libraries installed.

*  Download the Frey Face dataset from the provided link and place the "frey_rawface.mat" file in the "Freyface Dataset" directory.

*  Execute the code cells in the notebook sequentially by clicking on the "Play" button (triangle) or pressing Shift + Enter.

*  Observe the outputs and plots generated by the code to understand the performance of the Variational Autoencoders and the meaningful latent variables learned.

*  Remember to save your notebook periodically by clicking on "File" > "Save" or by using the keyboard shortcut Ctrl + S.

## Conclusion
The project successfully implements Variational Autoencoders and demonstrates meaningful latent representations using the Frey Face dataset. The provided code and readme offer a detailed guide to understanding and reproducing the results.

For any questions or issues, feel free to contact the author.

Author: Divya Rakheja

Contact: m22ai552@iitj.ac.in

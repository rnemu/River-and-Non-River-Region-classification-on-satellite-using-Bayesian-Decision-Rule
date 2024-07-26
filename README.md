# River and Non-River Region Classification on Satellite Images using Bayesian Decision Rule

This repository contains a project that classifies regions in satellite images into river and non-river regions using the Bayesian Decision Rule from scratch.
## Project Overview
### Annotate Image Points

The `annotate_image_points.py` script allows you to manually label points on the satellite images. This is an essential step to create a labeled dataset for training the Bayesian classifier.

### Bayesian Decision Rule

The`bdr_band_image.ipynb` notebook contains the implementation of the Bayesian Decision Rule from scratch. The steps include:
- Loading the annotated data.
- Estimating the parameters of the probability distributions for each class (river and non-river).
- Implementing the Bayesian Decision Rule to classify each pixel in the satellite image.
- Visualizing the classified regions.
- 
## Repository Structure

- `Data/`: This directory contains the dataset, which includes satellite images used for classification.
- `Code/`: This directory contains the scripts and notebooks for the project.
  - `annotate_image_points.py`: Script for annotating points on the satellite images.
  - `bdr_band_image.ipynb`: Jupyter notebook containing the code for implementing the Bayesian Decision Rule from scratch.
- `Output/`: This directory contains the output image showing the classified regions.
  - `Output.png`: Image with the classified river and non-river regions.
- `README.md`: This file, providing an overview of the project.

## Requirements

- Python 3.x
- numpy
- matplotlib
- scikit-learn
- opencv-python
- rasterio
- Jupyter Notebook

You can install the required packages using the following command:

```bash
pip install numpy matplotlib scikit-learn opencv-python rasterio jupyter

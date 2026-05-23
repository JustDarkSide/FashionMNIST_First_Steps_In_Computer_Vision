## Convolutional Neural Network and Fully-Connected Perceptrons performance comparison

This project provides a comparative performance analysis between standard Fully-Connected Neural Networks (Linear and Non-Linear Perceptrons) and a Convolutional Neural Network (CNN) trained on the FashionMNIST dataset.

Built entirely in **PyTorch**, this notebook demonstrates the fundamental mechanics of deep learning architectures, custom training loops, and multi-class evaluation metrics. All visualizations, code, and detailed charts are contained within the primary Jupyter Notebook.
## Key Findings and Error Analysis :gear: :wrench: 

#### Architecture Performance :bar_chart:
The Convolutional Neural Network (CNN) model significantly outperformed both standard and non-linear perceptrons in terms of accuracy 

#### Training :running:
The amount of epochs was limited to just 20 for all models. If the number of epochs were higher, standard and non-linear perceptrons would likely start overfitting. This phenomenon is definitely unwanted

#### Error Analysis :no_entry_sign:
The Confusion Matrix of model "Model2" shows that it classifies most of the test samples correctly, however it also presents a tendency of misclassifying "Shirt" category predicting "T-shirt/top" instead.  


## Tech Stack & Project Info

![Static Badge](https://img.shields.io/badge/python-%3E%3D3.12.6-royalblue?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Static Badge](https://img.shields.io/badge/project_status-completed-brightgreen?style=for-the-badge)


## How to Run

1. Clone this repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install torch torchvision torchmetrics mlxtend matplotlib pandas numpy seaborn

3. Run the **notebooks/fashion_mnist_architecture_comparison.ipynb** file to view the training loops, charts, and complete evaluation.


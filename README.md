# PyTorch ANN Model

This repository contains implementations of Artificial Neural Networks (ANNs) using PyTorch. The focus is on exploring various techniques and optimizations for training ANNs on different datasets and hardware setups.

## Notebooks

### 1. ANN Fashion MNIST Optimized
- **File**: `ANN_fashion_mnist_optimized.ipynb`
- **Description**: This notebook demonstrates the training of an ANN on the Fashion MNIST dataset with optimized hyperparameters and training techniques.

### 2. ANN on GPU
- **File**: `ANN_on_GPU.ipynb`
- **Description**: This notebook explores the use of GPU acceleration for training ANNs, showcasing the performance improvements over CPU-based training.

### 3. ANN via Hyperparameter Optimization (Optuna)
- **File**: `ANN_via_hyperparameter(optuna).ipynb`
- **Description**: This notebook uses the Optuna library to perform hyperparameter optimization for training ANNs, aiming to achieve the best possible model performance.

## Requirements

- Python 3.8+
- PyTorch
- Optuna (for hyperparameter optimization)
- Jupyter Notebook

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd pytorch_ANN_model
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the desired notebook in Jupyter:
   ```bash
   jupyter notebook
   ```

## License

This project is licensed under the MIT License.
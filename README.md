# baby-names-neural-net
Baby Name Generator Using Character-Level Neural Network Language Model based on the 2003 paper  "A Neural Probabilistic Language Model" by Yoshua Bengio et al that uses a Multi-layer Perceptron for language modeling.

## Project Overview
This repository contains two Jupyter notebooks focused on building and fine-tuning a neural network to generate baby names. The first notebook demonstrates the basic implementation of a neural network for generating baby names, while the second notebook dives deeper into fine-tuning the model by analyzing the activations of the neural network.

## Notebooks

### 1. Baby Names Neural Network
This notebook walks through the process of building a neural network to generate baby names. It covers data preprocessing, model architecture, training, and evaluation.

**Key Sections**:
- **Data Preprocessing**: Loading and cleaning the baby names dataset.
- **Model Architecture**: Defining the neural network using PyTorch.
- **Training the Model**: Training the network and tracking performance metrics.
- **Evaluating the Model**: Generating new baby names and evaluating their quality.

### 2. Fine-Tuning the Baby Names Generator (A Deeper Dive Into The Activations of My Neural Network)
This notebook takes a deeper dive into fine-tuning the neural network by analyzing the activations of the network. This analysis helps in understanding how different parts of the network contribute to the generation process and can be used to improve the model further.

**Key Sections**:
- **Activations Analysis**: Visualizing and interpreting the activations of the neural network layers.
- **Fine-Tuning Techniques**: Applying insights from the activation analysis to fine-tune the model.
- **Improved Results**: Evaluating the improvements in the generated baby names after fine-tuning.

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed:
- Python 3.6 or higher
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

You can install the necessary packages using `pip`:

```bash
pip install torch numpy pandas matplotlib jupyter
```

### Running the Notebooks
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/ahsanjahangirmir/baby-names-neural-net.git
    cd baby-names-neural-net
    ```

2. **Open Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

3. **Run the Notebooks**:
    - Open `baby_names_neural_net.ipynb` and run all cells to train and evaluate the basic neural network.
    - Open `activations_deep_dive.ipynb` and run all cells to analyze the activations and fine-tune the model.

## Usage
- **Training the Model**: Follow the steps in the `baby_names_neural_net.ipynb` notebook to train the model on the baby names dataset.
- **Generating Names**: After training, use the trained model to generate new baby names.
- **Fine-Tuning**: Use the `activations_deep_dive.ipynb` notebook to further fine-tune the model based on activation analysis.

## Contributing
We welcome contributions to improve the project. If you would like to contribute, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or inquiries, please contact [25100325@lums.edu.pk](mailto:25100325@lums.edu.pk).

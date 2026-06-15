# Handwritten Digit Classification with PyTorch

> Academic machine learning notebook for classifying handwritten digits from the MNIST dataset using a fully connected neural network in PyTorch.

## Project Overview

This project demonstrates a complete introductory deep learning workflow: loading the MNIST dataset, preprocessing image tensors, building a neural network, training the model, and evaluating classification performance.

The notebook was developed as part of academic practical work in machine learning.

## Dataset

The project uses the **MNIST** handwritten digit dataset, downloaded automatically through `torchvision.datasets.MNIST`.

## Technologies

| Category | Tools |
|---|---|
| Language | Python |
| Notebook | Jupyter / Google Colab |
| Deep Learning | PyTorch, TorchVision |
| Data Processing | NumPy |
| Visualization | Matplotlib |

## Repository Structure

```text
handwritten-digit-classification-pytorch/
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
└── notebooks/
    └── mnist_fully_connected_network.ipynb
```

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/mnist_fully_connected_network.ipynb
```

The dataset will be downloaded automatically when the notebook is executed.

## Skills Demonstrated

- Neural network training with PyTorch
- Image classification workflow
- Tensor manipulation and preprocessing
- Reproducible experiments with random seeds
- Model evaluation in Jupyter Notebook

## Author

**Manassé Makuikila Lusaku**

## License

MIT License

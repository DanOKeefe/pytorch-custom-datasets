# Effective Data Handling with Custom PyTorch Dataset Classes

Training machine learning models involves carefully managing and processing your training data. The examples in this repository demonstrate how to build custom PyTorch Dataset classes to efficiently handle data during training.

This repository contains two examples:

1. **Custom Dataset for the Titanic Dataset**
- Tabular data
- Entire dataset can fit into memory
- K-Fold cross validation
  
2. **Custom Dataset for the Food-101 Dataset**
- Image data
- Data is loaded from disk and augmented each time a batch is requested because the entire dataset does not fit into memory
- Transfer learning from a pretrained vision transformer model

# How to use

1. Clone the repo

```python
git clone https://github.com/DanOKeefe/pytorch-custom-datasets.git
cd pytorch-custom-datasets
```

2. Install dependencies
- PyTorch
- NumPy
- pandas
- scikit-learn
- tqdm
- torchvision
- PIL

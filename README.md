# Brain Tumor Classifier

This repository is part of a public portfolio and showcases a full pipeline for classifying brain tumor MRI images.

## Project Structure
- `notebooks/00_data_pretraitement.ipynb`: image preprocessing and augmentation.
- `notebooks/01_data_prep.ipynb`: data exploration and preparation.
- `notebooks/02_data_modeling.ipynb`: training convolutional neural networks to distinguish among `brain_glioma`, `brain_menin`, and `brain_tumor` images.
- `src/`: placeholder for reusable Python code.

The dataset comes from [HuggingFace](https://huggingface.co/datasets/Alwaly/Brain_Cancer-cancer).

## Installation
1. Create and activate a Python virtual environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Open the notebooks in order to reproduce the pipeline:
```bash
jupyter notebook notebooks/00_data_pretraitement.ipynb
```

## Results
After training for several epochs, the best CNN achieved:
- Validation accuracy: **0.849**
- Test accuracy: **0.839**

## Contributing
This repository is a starting point and showcases my first attempt at training a convolutional neural network.
Potential directions for improving the project include:

- experimenting with deeper or pre-trained architectures to boost accuracy
- running hyperparameter searches and cross-validation for more robust results
- enriching data augmentation and regularization to reduce overfitting
- packaging the model for inference or deployment
- adding metrics such as precision, recall, or confusion matrices to evaluate performance

## License
This project is distributed under the MIT License.
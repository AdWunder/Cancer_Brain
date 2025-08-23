# Brain Tumor Classifier

This repository is part of a public portfolio and provides a complete pipeline example for classifying brain tumors from MRI images.

## Project Structure
- `notebooks/00_data_pretraitement.ipynb`: image augmentation and preprocessing.
- `notebooks/01_data_prep.ipynb`: data exploration and preparation.
- `notebooks/02_data_modeling.ipynb`: training machine learning models to classify images into three categories (`brain_glioma`, `brain_menin`, `brain_tumor`).
- `src/`: space reserved for reusable Python code.

The dataset used is available on [HuggingFace](https://huggingface.co/datasets/Alwaly/Brain_Cancer-cancer).

## Installation
1. Create and activate a Python virtual environment.
2. Install the dependencies:
```bash
   pip install -r requirements.txt
   ```

## Usage
Open the notebooks in order to reproduce the pipeline:
```bash
jupyter notebook notebooks/00_data_pretraitement.ipynb
```

## Contributions
Suggestions and improvements are welcome. Feel free to open an issue or pull request.

## License
This project is distributed under the MIT license.

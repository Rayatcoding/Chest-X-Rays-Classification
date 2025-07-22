# Chest-X-Rays-Classification

This project implements a convolutional neural network (CNN) to classify chest X-ray images as either normal or showing signs of pneumonia. It was completed as part of a deep learning course project.

## Dataset

- Source: [Kaggle - Chest X-ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- The dataset includes chest X-rays labeled as either `NORMAL` or `PNEUMONIA`.

## Approach

- Used a custom CNN architecture (not based on pre-trained models).
- Applied data preprocessing and augmentation to improve generalization.
- Trained the model using PyTorch.
- Evaluated performance using accuracy, loss, and ROC curves.

## Results

- Achieved validation accuracy around 87% after tuning.
- ROC curves show good separation between classes.

## File Structure

- `DeepLearn_Final_Project.ipynb`: Main training and evaluation notebook.
- `data/`: Folder for dataset (not included in repo due to size).
- `models/`: Saved model checkpoints (optional).

## Future Work

- Try transfer learning with pretrained networks (e.g., ResNet).
- Convert model to a deployable API (e.g., Flask/FastAPI).
- Optimize for edge inference (e.g., using NVIDIA TensorRT or Jetson Nano).

## How to Run

1. Download and extract the dataset into a folder called `data/`.
2. Open and run all cells in the Jupyter notebook `DeepLearn_Final_Project.ipynb`.

## Author

- Yiming Ray (rayatcoding)

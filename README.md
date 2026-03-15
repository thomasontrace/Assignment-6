# Assignment 6: Building Your First Neural Network

## Overview
This assignment builds feedforward neural networks to classify human activities from sensor data. You'll experiment with different architectures (varying depth and width), compare performance against traditional machine learning approaches (PCA + Random Forest from Unit 7), and learn when neural networks justify their added complexity.

## Dataset
The project uses the [Human Activity Recognition (HAR) dataset](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones) containing sensor readings from smartphones to classify 6 different human activities:
- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying

The dataset contains 561 features derived from accelerometer and gyroscope sensor data.

## File Structure
```
Assignment-6/
├── README.md               # Project documentation
├── starter_notebook.ipynb  # Main Jupyter notebook with assignments
└── data/
    ├── train.csv           # Training dataset (sensor features + activity labels)
    └── test.csv            # Test dataset (sensor features + activity labels)
```

## Prerequisites
- Python 3.x
- Jupyter Notebook or VS Code with Jupyter extension

## Required Libraries
```
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow
```

## How to Run

### 1. Install Dependencies
First, install the required packages. You can run this from the first code cell in the notebook:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```

### 2. Open the Notebook
Open `starter_notebook.ipynb` in Jupyter Notebook or VS Code.

### 3. Execute the Notebook
Work through the notebook sequentially from top to bottom. The notebook is structured as a guided assignment with TODO comments indicating where you need to write code.

## Submission
After completing all steps and reflections:
```bash
git add .
git commit -m 'completed neural networks assignment'
git push
```
Submit your GitHub repository link on the course platform.
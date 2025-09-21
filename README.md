# Medical Imaging for Cancer Diagnosis using VGG16

This repository contains a deep learning project for **cancer diagnosis from MRI images** using **Transfer Learning (VGG16)** with TensorFlow/Keras.  

## Features
- MRI image preprocessing with `ImageDataGenerator`
- Transfer Learning with pretrained **VGG16**
- Model training, validation, and evaluation
- Confusion matrix and accuracy visualization

## Project Structure
```
Cancer-Medical-Imaging/
│── MRI.ipynb           # Main Jupyter notebook
│── requirements.txt    # Python dependencies
│── README.md           # Project documentation
│── .gitignore          # Ignore unnecessary files
└── data/               # (Place MRI dataset here if needed)
```

## Requirements
Install dependencies via:
```bash
pip install -r requirements.txt
```

## Dataset
- MRI images (not included in this repo).
- Update the `data/` folder with MRI dataset before running.

## How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/Cancer-Medical-Imaging.git
   cd Cancer-Medical-Imaging
   ```
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook MRI.ipynb
   ```

## Results
- Model performance is visualized using accuracy/loss plots and confusion matrix.

##  Technologies Used
- Python 3.x
- TensorFlow
- Keras
- Scikit-learn
- Matplotlib
- Seaborn
- Numpy
- Pandas

## Author
- Rushikesh Khot

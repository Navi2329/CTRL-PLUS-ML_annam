# README.md

## Challenge 1: Soil Type Classification (Multiclass)

This project aims to classify soil images into one of four categories: Alluvial, Black, Clay, or Red, using deep learning. The model is trained to recognize soil characteristics based on image features such as texture and color. The final score is based on the **minimum F1-score** across all classes, encouraging balanced performance.

### Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/Navi2329/CTRL-PLUS-ML_annam.git
   cd CTRL-PLUS-ML_annam
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/Mac
   env\Scripts\activate     # For Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running Instructions

1. Open the project in your preferred code editor.
2. Run the script or notebook to:
   - Load and preprocess the dataset
   - Train the model (EnhancedSOILNet or any other model)
   - Evaluate model performance (F1-score, classification report)
   - Generate and save final predictions

> If you're using Kaggle, upload the dataset (or use the preloaded dataset) and adjust the dataset path in the notebook accordingly (e.g., `../input/dataset-name/`).

## Challenge 2: Soil Image Binary Classification (One-Class)

This task involves classifying whether an image is a **soil image or not** using binary classification. You can use a pre-trained model like ResNet as a feature extractor and fine-tune it for one-class classification based on soil images.

### Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/Navi2329/CTRL-PLUS-ML_annam.git
   cd CTRL-PLUS-ML_annam
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/Mac
   env\Scripts\activate     # For Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running Instructions

1. Open the project in your preferred code editor.
2. Run the script or notebook to:
   - Load and preprocess the binary dataset
   - Train the model using positive soil image data
   - Predict whether test images are soil or not

> For Kaggle: Upload the dataset (or use the preloaded dataset), and update the paths in the notebook to reflect Kaggle's directory structure (e.g., `../input/dataset-name/`).

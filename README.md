# Sentiment Analysis Project

This project implements sentiment analysis using a machine learning model. It consists of two primary components:

- **Model Training and Saving:**  
  The notebook `Sentiment Analysis.ipynb` is used to build and train the model. After training, the model is saved to a persistent drive for later use.

- **Model Loading and Inference:**  
  The notebook `Loaded_model.ipynb` contains the code needed to load the saved model from the drive and use it to make predictions on new data.

---

## Overview

The sentiment analysis model is designed to classify text into categories such as positive, negative, or neutral. The process is divided into two main phases:

1. **Training Phase:**  
   - Implements data preprocessing, feature extraction, model building, training, evaluation, and saving of the trained model.
   
2. **Inference Phase:**  
   - Loads the pre-trained model and processes new text inputs to predict their sentiment.

---

## Installation

Follow these instructions to set up your environment:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/sentiment-analysis.git
   cd sentiment-analysis
   ```

2. **Set Up a Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Unix/Mac
   # or
   venv\Scripts\activate  # For Windows
   ```

3. **Install Necessary Packages:**

   Although there is no dedicated `requirements.txt` file, ensure that you have installed the necessary packages such as `numpy`, `pandas`, `scikit-learn`, and a machine learning framework (e.g., `tensorflow`/`keras`) based on the dependencies used in the notebooks. For example:

   ```bash
   pip install numpy pandas scikit-learn tensorflow
   ```

   Adjust these installations to match the specific libraries and versions utilized in your code.

---

## Usage

### Training the Model

1. **Launch the Training Notebook:**

   Open the `Sentiment Analysis.ipynb` notebook in your preferred Jupyter Notebook environment (JupyterLab, Jupyter Notebook, or VS Code).

2. **Execute the Notebook:**

   Run each cell in sequential order. The notebook will:
   - Load and preprocess your training data.
   - Define and compile the sentiment analysis model.
   - Train the model, evaluate its performance, and save it to your drive.

### Loading and Using the Model

1. **Launch the Inference Notebook:**

   Open the `Loaded_model.ipynb` notebook in your Jupyter environment.

2. **Load the Saved Model:**

   The notebook contains code that retrieves the pre-trained model from the drive. Be sure to update any file paths if needed.

3. **Make Predictions:**

   Execute the cell(s) responsible for running predictions. Input your text data to receive sentiment predictions, categorized as positive, negative, or neutral.

---

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for more details.

---

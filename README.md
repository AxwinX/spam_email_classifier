# Spam Email Classifier

## Overview
This project is a **Spam Email Classifier** that uses **Logistic Regression** to distinguish between spam and non-spam (ham) emails. The classifier is trained on a labeled dataset of emails and extracts relevant features to enhance classification accuracy.

## Dataset
The dataset used for this project was sourced from **Kaggle** and can be downloaded from the following link:
- **Dataset Download**: [combined_data.csv](https://www.mediafire.com/file/26zszufu23tergy/combined_data.csv/file)
- **Original Kaggle Source**: [Email Spam Classification Dataset](https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset)

## Features Extracted
The classifier utilizes the following features:
- **Email length**
- **Frequency of special characters (e.g., !, $, @)**
- **Presence of spam-related keywords (e.g., "win", "free", "cash")**
- **TF-IDF vectorization of email text**

## Algorithm Used
The classification is performed using **Logistic Regression** (MultinomialNB also tested), a simple yet effective algorithm for binary classification tasks. The model is trained using the Scikit-Learn library in Python.

## Project Files
- `spam_email_classification.ipynb` - Jupyter Notebook containing the data preprocessing, feature extraction, model training, and evaluation steps.
- `requirements.txt` - List of dependencies required to run the project.

## Installation and Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/spam-email-classifier.git
   cd spam-email-classifier
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook spam_email_classification.ipynb
   ```

## Model Evaluation
The classifier achieves high accuracy on the test dataset. Performance metrics include:
- **Accuracy**: ~95%
- **Precision**: High precision for spam detection
- **Recall**: Effectively detects spam emails while minimizing false positives

## Credits
- Dataset: [Kaggle - Email Spam Classification Dataset](https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset)

## License
This project is open-source and available under the MIT License.

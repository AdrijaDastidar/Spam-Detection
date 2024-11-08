# 📧 Spam Detection using Machine Learning

![Spam Detection](https://img.shields.io/badge/Spam-Detection-brightgreen.svg) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg) ![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg) 

## 📜 Table of Contents

- [📝 Introduction](#-introduction)
- [📊 Dataset](#-dataset)
- [🛠️ Installation](#️-installation)
- [📁 Project Structure](#-project-structure)
- [🚀 Usage](#-usage)
- [📈 Results](#-results)
- [🛠️ Technologies Used](#️-technologies-used)
- [📧 Contact](#-contact)

## 📝 Introduction

This project is a **Spam Detection** system that classifies emails as **Spam** or **Ham** using various Machine Learning algorithms. The goal is to filter out spam messages effectively by leveraging Natural Language Processing (NLP) techniques.

## 📊 Dataset

The dataset used in this project contains email messages labeled as either **Spam** or **Ham**. The dataset has two columns:

- **Category**: Indicates whether the email is 'spam' or 'ham'
- **Message**: The content of the email

The dataset can be downloaded using the following [Google Drive link](https://drive.google.com/uc?id=1PWL9JWCTa6a2N6TffUObhcl6TuLcwgI4).

## 🛠️ Installation

To run this project locally, you need to have Python and Jupyter Notebook installed.

### Step 1: Clone the repository

```bash
git clone https://github.com/yourusername/spam-detection.git
cd spam-detection
```

### Step 2: Install the required libraries

Open your terminal and run:

```bash
pip install numpy pandas scikit-learn gdown
```

### Step 3: Launch Jupyter Notebook

```bash
jupyter notebook
```

Then, open the `spam_detection.ipynb` file.

## 📁 Project Structure

```
spam-detection/
├── spam_detection.ipynb  # Jupyter Notebook with the complete code
└── README.md             # Project documentation
```

## 🚀 Usage

1. **Open the Jupyter Notebook**: After cloning the repository, navigate to the folder and open the `spam_detection.ipynb` file.

2. **Run the cells sequentially**: The notebook is structured to guide you through data loading, preprocessing, model training, evaluation, and predictions.

3. **Predict on custom emails**: Modify the `input_mail` list in the last section of the notebook to classify your custom emails:

    ```python
    input_mail = [
        "Hello, how are you doing today?",
        "Congratulations! You've won a $1000 gift card. Claim now!"
    ]
    ```

## 📈 Results

The following models were tested, and their performance is summarized below:

| Model                  | Test Accuracy | Precision | Recall | F1-Score |
|------------------------|---------------|-----------|--------|----------|
| Logistic Regression    | 98.7%         | 97.5%     | 98.0%  | 97.7%    |
| Random Forest          | 97.8%         | 96.8%     | 97.0%  | 96.9%    |
| K-Nearest Neighbors    | 95.3%         | 94.1%     | 93.5%  | 93.8%    |
| Decision Tree          | 96.2%         | 95.5%     | 95.0%  | 95.2%    |
| Support Vector Machine | 98.0%         | 96.7%     | 97.3%  | 97.0%    |

## 🛠️ Technologies Used

- **Python 3.8+**
- **Jupyter Notebook**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Scikit-learn** for machine learning models
- **TfidfVectorizer** for text feature extraction

## 📧 Contact

Feel free to reach out for any questions or suggestions:
- Email: adrijadastidar@example.com

---

To fix the issue with the Table of Contents links not working, you need to adjust the links to match GitHub's Markdown anchor link format. GitHub automatically converts headings into anchor links, typically by making them lowercase and replacing spaces with hyphens. Special characters are also removed.

Here's the updated `README.md` with corrected anchor links:

---

# email_spam_detection
# Email Spam Detection System

A machine learning-based system for detecting **spam** emails using Python and scikit-learn. This project applies natural language processing (NLP) techniques and classification algorithms to automatically identify spam messages, improving email security and efficiency.

---

## Project Overview

Email spam is a critical issue affecting productivity and security. This project leverages **machine learning** to classify emails as either **spam** or **ham (non-spam)**. The system includes data preprocessing, feature extraction, model training, and performance evaluation.

---

## Key Features

- **Text Preprocessing:** Clean and normalize email text  
- **Feature Extraction (TF-IDF):** Converts words into numbers. Words that appear frequently in a specific email but rarely across all emails get higher importance.  
- **Classification:** Support Vector Machine (SVM) with linear kernel  
- **Performance Metrics:** Accuracy, Precision, Recall, F1-score  
- **Scalable:** Handles large email datasets efficiently 
---

## Project Structure

| File / Folder | Description |
|---------------|-------------|
| `data/Spam_Email_Detection.xlsx` | Original email dataset |
| `notebooks/` | Jupyter notebooks for preprocessing, encoding, and model training |
| `scripts/` | Python scripts for feature extraction, model training, and evaluation |
| `README.md` | Project documentation and instructions |

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/rajnk654/email_spam_detection.git
cd email_spam_detection

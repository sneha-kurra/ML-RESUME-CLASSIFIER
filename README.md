# Resume Categorization using NLP & Machine Learning

A machine learning-based system that automatically classifies resumes into job domains such as Data Science, Web Development, HR, and more. 
This project uses NLP techniques and supervised learning to help recruiters sort resumes efficiently.

##Features
- Classifies resumes based on their content
- Applies Natural Language Processing (NLP) for text cleaning
- Uses TF-IDF for feature extraction
- Trains a machine learning model (e.g., Naive Bayes / Logistic Regression)
- Evaluates performance with accuracy, confusion matrix, etc.

## Tech Stack
- **Python**
- **Pandas / NumPy**
- **Scikit-learn**
- **NLP (TF-IDF, Stopword removal)**
- **Matplotlib / Seaborn** (optional for visualization)

## Dataset
The dataset contains resumes and their corresponding job role categories.

```csv
| Resume                          | Category         |
|--------------------------------|------------------|
| "Skilled in Python and ML..."  | Data Science     |
| "HTML, CSS, JavaScript..."     | Web Development  |
| ...                            | ...              |

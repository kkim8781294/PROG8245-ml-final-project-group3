# PROG8245-ml-final-project-group3

## Team Members
- Enuie Jo
- Jiho Jun
- Kihoon Kim

## How to Run  
1. Clone the repository: git clone 'Repo URL(Change)'  
2. Create a Python virtual environment & Activate  
3. Install dependencies: pip install -r requirements.txt  
4. Run the Jupyter Notebook: TextClassificationFinalProjectGroup3.ipynb  

## Dataset Description  

### 1. Clickbait Headline Dataset
For this project, we use the **Clickbait Headline Classification Dataset** from Kaggle.  
It contains **32,000 news headlines**, each labeled as either **clickbait (1)** or **non-clickbait (0)**.

The headlines were collected from two categories of news sources:

- **Clickbait sources:**  
  BuzzFeed, Upworthy, ViralNova, ScoopWhoop, Thatscoop  
  (These sources use curiosity-driven or sensational titles.)

- **Non-clickbait sources:**  
  The New York Times, The Guardian, WikiNews, The Hindu  
  (These follow traditional fact-based journalism.)

The dataset is **balanced** with nearly equal instances of both classes, making it ideal for binary supervised learning.

## Dataset Links
- Kaggle Dataset (Clickbait Headline Dataset):
https://www.kaggle.com/datasets/amananandrai/clickbait-dataset 

## Notebook Structure
1. Data Loading & Preprocessing  
2. TF-IDF Feature Extraction  
3. Baseline Model (Naive Bayes)    
4. Dimensionality Reduction (SVD)  
5. Logistic Regression + SVD  
6. Dimensionality Reduction (PCA)  
7. Logistic Regression + PCA  
8. Final Comparison & Visualization  
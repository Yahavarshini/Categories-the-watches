# Categories-the-watches using Machine Learning

This project involves an end-to-end machine learning pipeline to classify watches into categories like Smart, Analog, and Digital using both **unsupervised** and **supervised learning**.

## Project Highlights

- **Data Collection**: Web-scraped watch data from Amazon using SerpAPI.
- **Database Handling**: Data pushed to MySQL using SQLAlchemy and retrieved via MySQL Connector.
- **EDA**: Visualized distributions of price, ratings, and reviews; cleaned and processed text fields.
- **NLP**: Applied tokenization, stopword removal, lemmatization, POS tagging (nouns), TF-IDF vectorization.
- **Dimensionality Reduction**: PCA retained 98% variance to speed up training and reduce overfitting.
- **Unsupervised Learning**: K-Means clustering to discover groups and label data (Smart, Analog, Digital).
- **Supervised Learning Models**:
  - Logistic Regression gives Best Accuracy
  - SVM, Random Forest, XGBoost, GBoost, KNN, Naive Bayes, Decision Tree
- **Evaluation**: Used cross-validation, test/train accuracy. Best generalization by Logistic Regression and SVM.

## Results

- Models achieved up to **99% accuracy** on test data.
- Logistic Regression and SVM showed strong performance with minimal overfitting.

## Future Scope

- Include watch images for deep learning-based classification.
- Deploy model as a web application for live predictions.
- Expand dataset from multiple e-commerce platforms.


## Getting Started

1. Clone the repo  
   `git clone https://github.com/your-username/watch-classification.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Run analysis  
   `python src/main.py`

---

**Author**: Yahavarshini E 
**License**: MIT  



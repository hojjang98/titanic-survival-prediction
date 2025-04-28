# 🚢 Titanic - Predicting Survival with Machine Learning

Welcome aboard!  
This project is a hands-on machine learning exploration using the famous Titanic dataset from Kaggle.  
It’s basically the “Hello, World!” of data science — and here I am, diving in.

---

## 🎯 What I'm Trying to Do

- Explore the dataset (EDA)
- Make sense of the features and do some feature engineering
- Train machine learning models (coming soon!)
- Create and submit predictions to Kaggle
- Learn and have fun while building my data science workflow

---

## 🗂️ Folder Structure (Work in Progress)

titanic-survival-prediction/
│
├── data/                 
│   ├── raw/             
│   └── processed/      
│
├── notebooks/           
│   ├── 01_EDA.ipynb
│   ├── 02_Feature_Engineering.ipynb
│   ├── 03_Modeling.ipynb
│   └── 04_Final_Submission.ipynb
│
├── scripts/               
│   ├── preprocess.py      
│   ├── train.py           
│   └── utils.py          
│
├── models/               
│
├── submissions/           
│   └── submission_2025-04-25.csv
│
├── figures/               
├── requirements.txt       
├── README.md             
└── .gitignore            

---

## 🛠️ Tech Stack

- Python 3.10.1
- pandas & numpy
- matplotlib & seaborn
- scikit-learn
- xgboost (eventually)

---

## 📝 Progress Log

> This section will be updated as the project grows!

- [x] EDA
- [x] Feature Engineering
- [ ] Modeling
- [ ] Kaggle Submission
➡️ [titanic_EDA.ipynb](./notebooks/titanic_EDA.ipynb)

---

## 📈 Project Workflow

Here’s how I plan to approach the Titanic survival prediction:

1. **Exploratory Data Analysis (EDA)**  
   - Understand the structure of the data  
   - Check for missing values and class imbalance  
   - Visualize feature relationships (e.g., survival vs. age, class, sex)

2. **Feature Engineering**  
   - Create new features like "FamilySize", "Title", and "IsAlone"  
   - Handle missing values (e.g., Age, Fare)  
   - Encode categorical features

3. **Model Building**  
   - Try different classifiers: Logistic Regression, Random Forest, XGBoost  
   - Tune hyperparameters using cross-validation  
   - Compare model performance (accuracy, F1-score)

4. **Prediction & Submission**  
   - Select best model  
   - Generate predictions for test set  
   - Submit to Kaggle and evaluate result

5. **Future Plans**  
   - Try ensembling (voting, stacking)  
   - Use pipelines for cleaner workflow  
   - Document the whole process in scripts


## 🤓 Notes to Self

- Keep code clean and modular
- Try different models and compare results
- Don’t be afraid to mess up — it’s all part of the game

---

## ✍️ Author

Made with curiosity by [hojjang98](https://github.com/hojjang98)  
Feel free to clone, fork, or just take a peek 😄
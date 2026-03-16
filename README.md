# 🚢 Titanic - Machine Learning from Disaster

Kaggle competition entry predicting survival of Titanic passengers using Random Forest classifier.

## 🏆 Result
- **Public Score:** 0.75358 (75.3% accuracy)
- **Rank:** #10757 on leaderboard
- **Competition:** [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

## 🔗 Links
- **GitHub:** https://github.com/Gagana-r/titanic-kaggle
- **Kaggle Notebook:** https://www.kaggle.com/code/gaganasri22/titanicdisaster

## 📌 About
Predicting which passengers survived the Titanic shipwreck using passenger data like age, gender, and ticket class.

## 🛠️ Tech Stack
| Tool | Usage |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Scikit-learn | Machine learning (Random Forest) |
| Kaggle Notebooks | Development environment |

## ✨ Approach
1. **Exploratory Data Analysis** — Identified missing values and survival patterns
2. **Feature Engineering** — Selected 7 key features
3. **Preprocessing** — Handled missing values, encoded categorical variables
4. **Modeling** — Random Forest with 100 estimators
5. **Submission** — Generated predictions for 418 test passengers

## 📊 Features Used
- `Pclass` — Ticket class (1st, 2nd, 3rd)
- `Sex` — Gender (encoded: male=0, female=1)
- `Age` — Age in years (missing values filled with median)
- `SibSp` — Number of siblings/spouses aboard
- `Parch` — Number of parents/children aboard
- `Fare` — Passenger fare
- `Embarked` — Port of embarkation (encoded: S=0, C=1, Q=2)

## 📁 Project Structure
```
titanic-kaggle/
├── titanicdisaster.ipynb    # Main notebook with full analysis
├── train.csv                # Training data (891 passengers)
├── test.csv                 # Test data (418 passengers)
└── gender_submission.csv    # Sample submission format
```

## 🔑 Key Findings
- **Female passengers** had much higher survival rate than males
- **1st class passengers** survived more than 2nd and 3rd class
- **Children** had higher survival rates than adults
- Survival rate overall was **38.4%**

## 👩‍💻 Author
**Gagana R** — [GitHub](https://github.com/Gagana-r) | [LinkedIn](https://www.linkedin.com/in/gagana-sri-r-518488265/)

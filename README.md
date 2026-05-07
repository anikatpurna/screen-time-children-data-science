# Screen Time Patterns of Children and Teens (Ages 5-15)

A Data Science Exploration inspired by Anika and the Secret of the Cloud

By Anika Tabassum

---

## About This Project

This notebook investigates daily screen-time patterns among children ages 5-15 using a structured Kaggle dataset. Through descriptive statistics, exploratory visualizations, and machine learning models, I explore how screen time varies by age, gender, day type, and purpose (educational vs. recreational).

This project is personally inspired by my children's book, Anika and the Secret of the Cloud, which teaches kids about digital safety and where their data goes after they upload it to the cloud.

---

## Key Findings

- Screen time increases steadily with age across all groups
- Recreational usage consistently outpaces educational usage
- Weekend screen time is higher than weekday usage
- Screen time ranges from 0.44 to 8.19 hours per day
- No missing data — the dataset is clean but likely synthetic

---

## Dataset

| Property | Details |
|---|---|
| Source | Kaggle — Average Daily Screen Time for Children |
| Link | https://www.kaggle.com/datasets/ak0212/average-daily-screen-time-for-children |
| Rows | 198 |
| Variables | 6 |
| Type | Synthetic (structured for educational use) |

### Variables

- Age — Age of the child in years (5-15)
- Gender — Gender category of the child
- Screen Time Type — Educational, Recreational, or Total
- Day Type — Weekday or Weekend
- Average Screen Time (hours) — Average hours spent on screens per day
- Sample Size — Number of children represented in the group

---

## Tech Stack

### Libraries
- numpy, pandas, matplotlib, seaborn, plotly, scikit-learn

### Models Used
- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Linear and Polynomial Regression
- Ridge and Lasso Regression

---

## Getting Started

1. Clone the repository
git clone https://github.com/anikatpurna/screen-time-children-data-science

2. Install dependencies
pip install numpy pandas matplotlib seaborn plotly scikit-learn

3. Open Data_Science_Exploration_by_Anika_Tabassum.ipynb in Jupyter Notebook or Google Colab at https://colab.research.google.com

4. Download screen_time.csv from Kaggle and place it in the same folder as the notebook

---

## Why Real Data Could Not Be Used

- COPPA — prohibits release of identifiable data for children under 13
- FERPA — blocks schools from sharing student activity logs
- GDPR — prevents sharing child-related digital records in Europe

---

## Why This Project Matters

Screen time is not just a number. It represents how children learn, explore, and grow in an increasingly digital world. By understanding these patterns, we can support healthier habits, create safer online spaces, and help kids build awareness about the digital footprints they leave behind.

These insights connect directly to the purpose of my book, Anika and the Secret of the Cloud, where I teach children what happens to their data in a simple, gentle way.

---

## References

- Common Sense Media: https://www.commonsensemedia.org
- Pew Research Center: https://www.pewresearch.org
- OECD Digital Education Data: https://data.oecd.org
- UNICEF Global Kids Online: https://globalkidsonline.net
- CDC Youth Risk Behavior Surveillance: https://www.cdc.gov/healthyyouth/data/yrbs

---

## Author

Anika Tabassum
Author of Anika and the Secret of the Cloud

---

This project was created for educational purposes. All analysis is based on a synthetic dataset.

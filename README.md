# Advanced Churn Analysis in E-Commerce Harnessing Hybrid Machine Learning and Deep Learning Models

## 📋 Table of Contents
1. [Introduction](#introduction)
2. [EDA](#eda)
3. [Churn Analysis](#churn-analysis)
4. [Statistical Methods](#statistical-methods)
5. [Machine Learning Models](#machine-learning-models)
6. [Deep Learning Model](#deep-learning-model)
7. [PowerBI Dashboard](#powerbi-dashboard)
8. [Conclusion](#conclusion)

## 📊 Features Analyzed
- Churn
- Tenure
- PreferredLoginDevice
- CityTier
- WarehouseToHome
- PreferredPaymentMode
- Gender
- HourSpendOnApp
- NumberOfDeviceRegistered
- PreferedOrderCat
- SatisfactionScore
- MaritalStatus
- NumberOfAddress
- Complain
- OrderAmountHikeFromlastYear
- CouponUsed
- OrderCount
- DaySinceLastOrder
- CashbackAmount

## 🔬 Model Performance

| Model | Train Accuracy | Test Accuracy |
|-------|----------------|---------------|
| Logistic Regression | 0.708270 | 0.773204 |
| Support Vector Machine | 0.904278 | 0.878893 |
| Decision Tree | 1.000000 | 0.937087 |
| Random Forest | 1.000000 | 0.900990 |
| XGBClassifier | 1.000000 | 0.937282 |
| AdaBoostClassifier | 0.873314 | 0.815146 |

## 💡 Key Insights
- Multiple models were evaluated, with Decision Tree and XGBClassifier showing the highest test accuracy
- Perfect training accuracy (1.000000) was achieved by Decision Tree, Random Forest, and XGBClassifier
- All models show good performance, with test accuracies ranging from 77% to 94%

## 📈 Methodology
Our analysis follows a comprehensive approach:
1. **Exploratory Data Analysis (EDA)** - Understanding the data distribution and relationships
2. **Statistical Methods** - Applying statistical techniques to validate hypotheses
3. **Machine Learning Models** - Implementing various algorithms to predict churn
4. **Deep Learning Model** - Utilizing neural networks for complex pattern recognition
5. **Visualization** - Creating an interactive PowerBI dashboard for insights

## 🔧 Implementation Details

### Data Preprocessing
- Feature engineering on customer attributes
- Handling missing values and outliers
- Encoding categorical variables (PreferredLoginDevice, PaymentMode, etc.)
- Scaling numerical features (Tenure, HourSpendOnApp, etc.)

### Model Selection
- Tested multiple algorithms for comparison
- Cross-validation to ensure robust results
- Hyperparameter tuning for optimal performance

## 📊 PowerBI Dashboard
Our interactive dashboard visualizes:
- Churn rates across different customer segments
- Key performance indicators
- Feature importance and correlations

## 🚀 Usage

### Requirements
```
Python 3.8+
scikit-learn
xgboost
tensorflow
pandas
numpy
```

## 📂 Repository Structure
```
.
├── data/
├── models/
├── notebooks/
├── src/
├── dashboard/
└── README.md
```

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For questions or feedback, please [open an issue](https://github.com/Fathima1123/Advanced-churn-analysis-documentation-/issues) or contact the maintainers.

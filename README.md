# Supervised Learning on JEE Mains Marks Analysis (2013-2025)

A comprehensive machine learning project analyzing JEE (Joint Entrance Examination) Mains marks data from 2013 to 2025, implementing various supervised learning algorithms to predict student performance and rank categories.

## 📊 Project Overview

This project focuses on analyzing JEE Mains examination data spanning over a decade to understand patterns in student performance and develop predictive models for rank categorization. The analysis includes exploratory data analysis (EDA), feature engineering, and implementation of multiple machine learning algorithms with hyperparameter optimization.

## 🎯 Objectives

- Analyze JEE Mains marks distribution and trends from 2013 to 2025
- Perform comprehensive exploratory data analysis with visualizations
- Implement and compare multiple supervised learning algorithms
- Predict student rank categories based on subject-wise marks
- Optimize model performance using hyperparameter tuning
- Identify key factors influencing JEE Mains performance

## 📈 Dataset Description

The dataset contains **24,248 entries** with **13 features** including:

- **Temporal Data**: Exam year information
- **Student Demographics**: Age, gender, and background information
- **Subject-wise Marks**: Mathematics, Physics, Chemistry scores
- **Performance Metrics**: Total marks, rank, percentile
- **Additional Features**: Various categorical and numerical attributes

### Target Variable
Rank categories are classified into three groups:
- **Category 0**: Rank ≤ 50 (Top performers)
- **Category 1**: 50 < Rank ≤ 80 (Good performers)
- **Category 2**: Rank > 80 (Average performers)

## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning algorithms and tools
- **Google Colab** - Development environment

## 🤖 Machine Learning Models Implemented

1. **Random Forest Classifier**
2. **Decision Tree Classifier**
3. **Logistic Regression**
4. **AdaBoost Classifier** ⭐ (Best performing model)
5. **Linear Regression**

## 🏆 Model Performance

| Model | Accuracy | Notes |
|-------|----------|-------|
| **AdaBoost** | **92.28%** | Best performing model |
| Random Forest | ~90%+ | Strong baseline performance |
| Decision Tree | ~85%+ | Good interpretability |
| Logistic Regression | ~80%+ | Linear baseline |
| Linear Regression | ~75%+ | Regression approach |

*Note: All models were optimized using GridSearchCV for hyperparameter tuning*

## 📋 Usage Instructions

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Running the Analysis

1. **Clone the repository**
   ```bash
   git clone https://github.com/Yashas7206988696/Supervised-learning-on-Jee-mains-marks-from-year-2013-to-2025.git
   cd Supervised-learning-on-Jee-mains-marks-from-year-2013-to-2025
   ```

2. **Open the Jupyter Notebook**
   ```bash
   jupyter notebook Supervisedlearning.ipynb
   ```
   
   Or use Google Colab:
   - Upload the notebook to Google Colab
   - Run all cells sequentially

3. **Execute the Analysis**
   - Run cells step by step to see the complete analysis
   - Modify hyperparameters or try different models as needed
   - View visualizations and model performance metrics

## 🔍 Key Analysis Steps

1. **Data Loading and Preprocessing**
   - Load the JEE Mains dataset
   - Handle missing values and data cleaning
   - Feature engineering and transformation

2. **Exploratory Data Analysis (EDA)**
   - Statistical summaries and distributions
   - Correlation analysis between features
   - Visualization of trends and patterns

3. **Feature Engineering**
   - Target variable creation (rank categories)
   - Feature selection and scaling
   - Train-test split preparation

4. **Model Training and Evaluation**
   - Implement multiple ML algorithms
   - Cross-validation and performance metrics
   - Hyperparameter tuning with GridSearchCV

5. **Results Analysis**
   - Model comparison and selection
   - Feature importance analysis
   - Performance visualization

## 📊 Key Insights

- **Best Model**: AdaBoost Classifier achieved 92.28% accuracy
- **Feature Importance**: Subject-wise marks are strong predictors of rank categories
- **Data Quality**: Clean dataset with comprehensive coverage from 2013-2025
- **Performance Trends**: Ensemble methods outperformed individual classifiers

## 🚀 Future Enhancements

- [ ] Implement deep learning models (Neural Networks)
- [ ] Add time-series analysis for year-over-year trends
- [ ] Develop web application for real-time predictions
- [ ] Include more advanced feature engineering techniques
- [ ] Implement cross-validation strategies for better generalization
- [ ] Add model explainability using SHAP or LIME

## 📝 Project Structure

```
Supervised-learning-on-Jee-mains-marks-from-year-2013-to-2025/
│
├── README.md                    # Project documentation
├── LICENSE                      # MIT License
├── Supervisedlearning.ipynb    # Main analysis notebook
└── data/                       # Dataset files (if applicable)
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- JEE Mains examination data providers
- Scikit-learn library developers
- Google Colab for providing computational resources
- Open-source community for valuable tools and libraries

## 📧 Contact

Yashas - [GitHub Profile](https://github.com/Yashas7206988696)

Project Link: [https://github.com/Yashas7206988696/Supervised-learning-on-Jee-mains-marks-from-year-2013-to-2025](https://github.com/Yashas7206988696/Supervised-learning-on-Jee-mains-marks-from-year-2013-to-2025)

---

⭐ If you found this project helpful, please give it a star!

# 🍷 Wine Quality Prediction Using Machine Learning

## Overview
This project applies various data mining and machine learning techniques to predict wine quality based on physicochemical properties. The goal is to help producers identify high-quality wines and understand which components contribute most significantly to wine quality.

## 📊 Dataset
The dataset contains various chemical properties of wines, such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

And a quality score (target variable) ranging from 0 to 10.

## 🧹 Data Preprocessing
The data preparation phase included:
- **Exploratory Data Analysis (EDA)** to understand the distribution and relationships between variables
- **Outlier Detection** using box-plots to identify anomalous data points
- **Outlier Handling** via Mean/Median imputation to ensure data quality
- **Feature Scaling** to normalize the range of independent variables
- **Feature Selection** to identify the most important predictors of wine quality

## 🤖 Machine Learning Models
Several classification algorithms were implemented and compared:
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem
- **Random Forest**: An ensemble learning method using multiple decision trees
- **Support Vector Machine (SVM)**: A supervised learning model that analyzes data for classification

## 📈 Model Evaluation
The models were evaluated using:
- **Confusion Matrix**: To visualize the performance of classification algorithms
- **Accuracy Score**: To measure the overall correctness of the models
- **Precision, Recall, and F1-Score**: To assess the balance between false positives and false negatives

## 🏆 Results
The implemented models demonstrated strong predictive capabilities, with Random Forest generally outperforming the other algorithms. The most significant features affecting wine quality were identified as alcohol content, volatile acidity, and sulphates.

## 📝 Conclusion
This project successfully demonstrates how machine learning techniques can be applied to predict wine quality based on chemical properties. The insights gained can help winemakers focus on the most critical factors that influence quality.

## 🛠️ Technologies Used
- **Python** for programming and analysis
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for implementing machine learning algorithms

## 📚 How to Use
```bash
# Clone the repository
git clone https://github.com/Mhdd-24/Wine-Quality-Prediction.git

# Navigate to the project directory
cd Wine-Quality-Prediction-Machine-Learning

# Install required packages
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook Wine_Quality_Prediction.ipynb
```

## 🔍 Future Work
- Implement deep learning models for comparison
- Perform hyperparameter tuning to optimize model performance
- Develop a web application for real-time wine quality prediction
- Expand the dataset to include more wine varieties and regions

## 👨‍💻 Contributors
- Your Name Mhdd-24

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

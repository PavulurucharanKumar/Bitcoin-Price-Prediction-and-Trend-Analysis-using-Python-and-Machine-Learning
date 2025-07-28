# Bitcoin Price Prediction and Trend Analysis using Python and Machine Learning
# 🪙 Bitcoin Price Prediction Using ML

This project analyzes historical Bitcoin price data and predicts the closing price using **Linear Regression** model.

## 📁 Dataset

- Dataset: `btccoin.csv`
- Size: 350 MB (not uploaded here due to size limit)

> 📌 Full dataset can be loaded via Google Drive or split into smaller chunks for use.

---

##  Project Steps

### ✅ Step 1: Import Libraries
- pandas, numpy, matplotlib, seaborn
- sklearn for ML models

### ✅ Step 2: Load Dataset
- Reads the CSV and removes duplicates

### ✅ Step 3: Handle Missing Values
- Imputes missing values using median for numeric columns

### ✅ Step 4: Data Visualization
- Line plot of Bitcoin closing prices over time
- Correlation heatmap of features

### ✅ Step 5: Feature Selection & Train-Test Split
- Features: Open, High, Low, Volume
- Target: Close
- Split: 80% Train / 20% Test

### ✅ Step 6: Model Training
- Trains Linear Regression

### ✅ Step 7: Evaluation
- Calculates RMSE and R² 
- Plots Actual vs Predicted values

---

## 📊 Model Results

| Model                  | RMSE    | R² Score |
|------------------------|---------|----------|
| Linear Regression      | 10.46   | 1.00     |

---

## 📷 Plots

- Time series plot of Bitcoin closing price
- Heatmap of correlations
- Scatter plots: Actual vs Predicted prices

---

## 🚀 How to Run

1. Clone the repo  
2. Upload the dataset (or use the sample part)  
3. Run each step in `Google Colab` or Jupyter  

---

## 🔗 Note

- Full dataset is too large for GitHub.  
- Upload your CSV to Google Drive and read it via Colab if needed.  


---

## 📧 Contact

Feel free to reach out if you face any issues!



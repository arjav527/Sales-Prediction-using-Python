# 📈 Sales Prediction Using Python

## 📝 Project Description

This project demonstrates how to predict product sales using machine learning techniques. It leverages a dataset containing advertising budgets across different media channels (TV, Radio, Newspaper) and corresponding product sales figures. The goal is to build a model that accurately predicts sales based on advertising investments.

---

## 📂 Dataset

- **Columns**:
  - `TV`: Advertising budget on TV
  - `Radio`: Advertising budget on radio
  - `Newspaper`: Advertising budget on newspapers
  - `Sales`: Units of product sold

- **Shape**: 200 rows × 4 columns  
- **Source**: Included in the repository (`.csv` file)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for missing values (none found)
- Correlation analysis using heatmap
- Pair plots for feature relationships
- Visualizations showing impact of each feature on sales

---

## 🤖 Model Used

- **Linear Regression**  
  Trained to map advertising budgets to sales values.

---

## 📈 Model Evaluation

- **Train/Test Split**: 80/20
- **R² Score**: ~0.90
- **MSE**: Low
- The model performs well in identifying key factors affecting sales.

---

## 📌 Key Insights

- **TV advertising** has the highest positive impact on sales.
- **Radio** has a moderate effect.
- **Newspaper** contributes the least.

---

## 🚀 Future Enhancements

- Try other models like **Random Forest, XGBoost**
- Build a **Streamlit dashboard** for interactive prediction
- Incorporate more features (e.g., product type, location, seasonality)
- Deploy the model using **Flask or FastAPI**

---

## 📁 Project Structure

├── data/
│ └── advertising.csv
├── notebooks/
│ └── Sales_Prediction_Analysis.ipynb
├── images/
│ └── visualizations.png
├── README.md
└── requirements.txt




---

## 👨‍💻 Author

**Arjav Jain**  
Data Science Enthusiast  
📧 arjavjain062@gmail.com | 🌐 [GitHub](https://github.com/arjav527)

---

## 📌 License

This project is open-source and available under the [MIT License](LICENSE).

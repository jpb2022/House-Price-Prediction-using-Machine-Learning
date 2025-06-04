# 🧠 House Price Prediction using Machine Learning

This project involves building and comparing multiple regression models to predict house prices. The primary focus is on evaluating different models including Linear Regression, Decision Tree, Random Forest, and XGBoost. The performance of each model is analyzed using evaluation metrics and visualized for better understanding.

---

## 📁 Project Structure


---

## 🔍 Problem Statement

Accurately predict house prices using structured features like area, bedrooms, location, etc. The goal is to compare several machine learning models and identify the most accurate and efficient one for this regression task.

---

## 🧰 Technologies Used

- Python 3.8+
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 🧪 Models Evaluated

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **XGBoost Regressor**

---

## 📊 Evaluation Metrics

- **MAE** (Mean Absolute Error)
- **MSE** (Mean Squared Error)
- **RMSE** (Root Mean Squared Error)
- **R² Score** (Coefficient of Determination)

---

## 🏁 Results

| Model              | MAE        | MSE            | RMSE       | R²       |
|--------------------|------------|----------------|------------|----------|
| Decision Tree      | 44,279     | 3.54e+09       | 59,512     | 0.935    |
| Random Forest      | 22,773     | 8.98e+08       | 29,964     | 0.984    |
| **XGBoost**        | **18,426** | **5.43e+08**   | **23,310** | **0.990** |
| Linear Regression  | 113,303    | 2.32e+10       | 152,358    | 0.574    |

✅ **XGBoost** was the best performer across all metrics.

---

## 📈 Visualizations

- **Radar Chart** comparing normalized model performance across metrics
- **Bar Charts** showing individual metric values for each model

---

## ⚙️ How to Run

1. Clone the repo:
    ```bash
    git clone https://github.com/yourusername/house-price-prediction.git
    cd house-price-prediction
    ```

2. Install requirements:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook:
    ```bash
    jupyter notebook notebooks/house_price_modeling.ipynb
    ```

---

## 📌 Notes

- You may see GPU warnings for XGBoost if CUDA is not enabled. The model will fall back to CPU.
- The dataset used is assumed to be pre-cleaned and encoded. You can modify the notebook for preprocessing as needed.

---

## 📤 Future Improvements

- Add SHAP or LIME explanations for interpretability.
- Try LightGBM or CatBoost for further performance gains.
- Enable GPU training by installing `xgboost` with CUDA support.

---

## 🧑‍💻 Author

**Jitendra Kumar Gupta**  
M.Tech, IIT Kanpur | Data Scientist & ML Engineer  
[LinkedIn](https://linkedin.com/in/jitendra-gupta-1903) | [Email](mailto:jitendraguptaaur@gmail.com)

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` file for details.

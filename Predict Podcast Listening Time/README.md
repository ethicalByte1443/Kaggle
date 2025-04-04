# 🎧 [Predict Podcast Listening Time – Kaggle Playground Series S5E4](https://www.kaggle.com/competitions/playground-series-s5e4)

## 🏆 My Competition Score

- **📢 Public Score:** `16.49513`  
- **🥇 Best Score:** `16.49513 V2`  

---


## 🧪 My Approach

1. **🔄 Data Loading**  
   Loaded both training and test datasets using `pandas`.

2. **🧼 Handling Missing Values**  
   Used `fillna()` to fill missing values in the dataset with **column-wise mean values**.

3. **🧠 Categorical Encoding**  
   Applied encoding techniques (like Label Encoding or One-Hot Encoding) to convert categorical columns into numerical format suitable for model training.

4. **🧠 Ensemble Learning Models**  
   Utilized **Ensemble Learning** with the following models:
   - 🎯 **XGBoost**: Gradient boosting framework optimized for speed and performance.
   - ⚡ **LightGBM**: Fast, distributed, high-performance gradient boosting framework based on decision tree algorithms.
   - 🐱 **CatBoost**: Gradient boosting library that handles categorical features automatically and reduces the need for extensive preprocessing.

5. **🧮 Model Averaging / Blending**  
   Final predictions were obtained by **blending outputs** of the three models (e.g., simple average or weighted average) to improve generalization and reduce overfitting.

---

## 📝 Evaluation Metric

### 📉 Root Mean Squared Error (RMSE)

Submissions are scored on the **Root Mean Squared Error (RMSE)**, defined as:

\[
\text{RMSE} = \sqrt{ \frac{1}{N} \sum_{i=1}^{N} (y_i - \hat{y}_i)^2 }
\]

Where:  
- \( \hat{y}_i \) is the **predicted** value  
- \( y_i \) is the **actual** value  
- \( N \) is the number of instances  

---

## 📄 Submission File Format

For each `id` in the test set, you must predict the `Listening_Time_minutes` of the podcast.

The submission file must include a header and should look like this:


---

## 📅 Timeline

- **Start Date**: April 1, 2025  
- **Entry Deadline**: April 30, 2025  
- **Final Submission Deadline**: April 30, 2025  
- **Team Merger Deadline**: April 30, 2025  

⏰ *All deadlines are at 11:59 PM UTC unless otherwise noted.*  
🛠️ *Organizers reserve the right to update the timeline if necessary.*

---

## 🧠 About the Tabular Playground Series

The **Tabular Playground Series** aims to provide the Kaggle community with lightweight and practical challenges. These competitions are ideal for:

- Practicing **feature engineering** and **model tuning**
- Exploring **new algorithms**
- Building quick **end-to-end pipelines**
- Strengthening your **ML intuition**  
- Practicing submission handling and metric evaluation

Competitions are generally short (a few weeks), offering fast feedback cycles and flexible participation.

---

## 📊 Synthetically-Generated Datasets

To strike a balance between real-world relevance and secure testing:

- The datasets are **synthetically generated** using real-world distributions and naming conventions.
- Labels for test data remain hidden.
- This enables fair, public competitions without data leakage.
- Synthetic generation helps ensure fewer artifacts and richer structure.

> 📣 *Feedback is welcome to help improve future datasets!*

---

## 📚 Citation

Walter Reade and Elizabeth Park.  
**Predict Podcast Listening Time.**  
[https://www.kaggle.com/competitions/playground-series-s5e4](https://www.kaggle.com/competitions/playground-series-s5e4), 2025. Kaggle.


# Predicting Customer Purchases with a Decision Tree Classifier  

This project focuses on building a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their **demographic** and **behavioral data**. The **Bank Marketing dataset** from the UCI Machine Learning Repository is used to train and test the model.

---

## Dataset  
- **Source**: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)  
- **Description**: The dataset contains information on direct marketing campaigns (phone calls) by a Portuguese banking institution. It includes customer demographics, behavioral attributes, and whether they subscribed to a term deposit.  
- **Target Variable**:  
  - **`y`**: Whether the customer subscribed to a term deposit (`yes` or `no`).

---

## Project Objectives  
The primary objectives of this project are:  
1. **Preprocess the dataset**: Handle missing values, encode categorical features, and normalize the data.  
2. **Build and train a Decision Tree Classifier** to predict customer purchases.  
3. **Evaluate the model's performance** using accuracy, precision, recall, and F1-score.  
4. **Visualize the decision tree** to interpret the decision rules and key features impacting customer behavior.

---

## Tools Used  
- **Python**: Primary programming language.
- **Libraries**:  
  - `pandas` and `numpy` for data manipulation and preprocessing.  
  - `scikit-learn` for model building and evaluation.  
  - `matplotlib` and `seaborn` for data visualization.  

---

## Procedure 
1. **Download the Dataset**:  
   - Visit the UCI Machine Learning Repository at the link above.  
   - Download the Bank Marketing dataset in **CSV** format.  

2. **Data Preprocessing**:  
   - Handle missing values and outliers.  
   - Encode categorical variables (e.g., using One-Hot Encoding or Label Encoding).  
   - Normalize or scale numerical features if necessary.  

3. **Building the Decision Tree Classifier**:  
   - Split the dataset into **training** and **testing sets**.  
   - Train the **Decision Tree model** on the training data.  
   - Tune hyperparameters such as max depth, criterion (e.g., Gini or entropy), and min samples split.  

4. **Model Evaluation**:  
   - Evaluate the model's performance using metrics like **accuracy, precision, recall**, and **F1-score**.  
   - Use **confusion matrices** to understand misclassifications.  

5. **Visualization**:  
   - Plot the **decision tree** to interpret decision paths and key features.  
   - Use feature importance scores to identify influential variables.  

---

## Example Insights  
- Identifying customer segments more likely to purchase the product.  
- Understanding which features (e.g., age, job, contact type) have the greatest impact on customer behavior.  
- Determining the optimal decision rules for future marketing campaigns.  

---

## Conclusion  
This project demonstrates how a **Decision Tree Classifier** can effectively predict customer purchase behavior. With this model, businesses can better target customers and improve the efficiency of marketing campaigns.

---

## Future Improvements  
- Apply other classification models (e.g., Random Forest, Logistic Regression) for comparison.  
- Use **cross-validation** to further validate model performance.  
- Deploy the model using a web-based dashboard for real-time predictions.

---

## Author  
- **Akshat Soni**  

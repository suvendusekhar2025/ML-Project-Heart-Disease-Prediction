# ML-Project-Heart-Disease-Prediction
### **Heart Disease Prediction Using Machine Learning**  

This project focuses on predicting heart disease using a machine learning approach. The dataset used for this study is a **Heart Disease dataset** stored in a CSV file, consisting of **303 rows** and **14 columns**. The objective is to classify individuals as either having a **defective heart** or a **non-defective heart** based on relevant medical attributes.  

#### **Tools and Libraries Used:**  
- **Python Libraries:**  
  - numpy – for numerical computations.  
  - pandas – for data manipulation and preprocessing.  
- **Scikit-Learn (sklearn) Libraries:**  
  - train_test_split – for splitting the dataset into training and testing sets.  
  - LogisticRegression – as the primary classification model.  
  - accuracy_score – for evaluating model performance.  

#### **Methodology:**  
1. **Data Preprocessing:**  
   - The dataset was loaded and analyzed using Pandas.  
   - Data cleaning and preparation steps were performed to ensure proper model training.  
   
2. **Model Selection & Training:**  
   - The dataset was **split** into training and testing sets using train_test_split.  
   - The **Logistic Regression model** was chosen for classification.  
   - The model was trained using the training dataset.  

3. **Evaluation & Results:**  
   - The **accuracy score** for the training dataset was **85.12%**.  
   - The **accuracy score** for the test dataset was **81.96%**, indicating a strong predictive capability of the model.  

#### **Conclusion:**  
This project successfully demonstrates the ability of **Logistic Regression** to predict heart disease with significant accuracy. The model achieves a high performance on both training and test datasets, making it a useful tool for preliminary heart disease prediction. Further improvements can be made by exploring advanced models like Decision Trees, Random Forest, or Neural Networks to enhance accuracy and generalization.

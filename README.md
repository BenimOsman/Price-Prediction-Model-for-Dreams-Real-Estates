# Price-Prediction-Model-for-Dreams-Real-Estates
Created using Sample Data provided by Dreams Real Estates 


**Drive Link:** <br>
https://drive.google.com/drive/folders/1f4z46ky4mpV2UO9_8ofr6rrO5EdyznsG?usp=sharing

**Libraries Used:**
1. Scikit-learn: For building and evaluating machine learning models.
2. Pandas: For data manipulation and preprocessing.
3. NumPy: For numerical computations.
4. Matplotlib/Seaborn: For data visualization (if used).

**Methodology of the House Price Prediction Model:**
1. **Data Preparation**
   - The dataset is divided into training and testing sets to evaluate the model's performance on unseen data.
   - Strategies include removing data points, removing entire attributes, or imputing missing values with measures like mean or median.
2. **Model Building**
   - Data is scaled using Min-Max Scaling (Normalization) or Standardization to ensure consistent model input.
   - The workflow is automated by creating a pipeline that includes all preprocessing steps and the model itself.
3. **Model Selection and Evaluation**
   - An appropriate machine learning model is chosen for predicting house prices.
   - Cross-validation techniques are used to get a reliable estimate of the model's performance and reduce overfitting.
4. **Model Deployment**
   - The trained model is stored and validated on the test set.
   - The trained model is applied to make real-time house price predictions.

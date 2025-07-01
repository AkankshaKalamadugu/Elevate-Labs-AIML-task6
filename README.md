# Task 6: K-Nearest Neighbors (KNN) Classification

## 🎯 Objective
Understand and implement the K-Nearest Neighbors (KNN) algorithm for classification using the Iris dataset.

## 📂 Dataset
- **Name**: Iris Dataset
- **Features**: Sepal length, Sepal width, Petal length, Petal width
- **Target**: Species (Setosa, Versicolor, Virginica)

## 🧠 Concepts Covered
- Instance-based learning
- Euclidean distance
- Feature normalization
- Confusion matrix
- Decision boundaries

## 🛠️ Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## 📊 Model Implementation Steps
1. Load and explore the Iris dataset
2. Normalize features using `StandardScaler`
3. Train-test split
4. Train KNN classifier with different `k` values
5. Evaluate using accuracy score and confusion matrix
6. Visualize decision boundaries

## 📈 Accuracy Results
- Best accuracy observed at **k = 3**: `0.97`

## 📎 Files Included
- `knn_classifier.ipynb`: Jupyter Notebook with all code and visualizations
- `README.md`: This file
- `iris.csv`: Dataset used (optional, as it can be loaded from sklearn)

## 🧪 Interview Questions Answered
1. **How does KNN work?**  
   KNN finds the `k` nearest neighbors (based on distance) and classifies based on majority class.

2. **How do you choose the right K?**  
   Try different K values, evaluate using accuracy or cross-validation.

3. **Why is normalization important?**  
   KNN is distance-based, so all features must be on the same scale.

4. **Time complexity of KNN?**  
   Training: `O(1)`, Prediction: `O(n*d)` where `n` is training samples and `d` is dimensions.

5. **Pros and Cons of KNN?**  
   Pros: Simple, no training time.  
   Cons: Slow prediction, sensitive to irrelevant features and scale.

6. **Is KNN sensitive to noise?**  
   Yes, especially for small `k`.

7. **Multi-class handling?**  
   KNN supports it by majority voting.

8. **Role of distance metrics?**  
   Defines how neighbors are chosen. Common: Euclidean, Manhattan.

## Screenshots of Accuracy vs k & confusion matrix
<img width="724" alt="Accuracy vs k"  src="https://github.com/user-attachments/assets/3d8002fb-e11f-4a4b-a8f7-021767d20c81" />
  <img width="545" alt="confusion matrix" src="https://github.com/user-attachments/assets/65779921-92a5-4993-8dcd-7320a231e68f" />



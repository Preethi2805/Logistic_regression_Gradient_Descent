### **Project Tasks:**

1. **Task 1: Logistic Regression Implementation**
   - **Objective:** Implement a logistic regression model and compute the gradient of the cross-entropy loss with respect to the parameters.
   - **Steps:**
     - Define a function to compute the predicted probability of the positive class.
     - Implement a function to calculate the gradient of the cross-entropy loss.
     - Test the model on a synthetic dataset and verify the correctness of the gradient.
   
2. **Task 2: Decision Tree on the Iris Dataset**
   - **Objective:** Fit a decision tree to the Iris dataset, split the data into training and testing sets, and visualize performance with a multiclass confusion matrix.
   - **Steps:**
     - Train the decision tree on the Iris dataset using a 67%/33% train/test split.
     - Use the confusion matrix from `sklearn.metrics` to visualize performance.
     - Compare your implementation with `sklearn.tree.DecisionTreeClassifier`.
   
3. **Task 3: Random Forest on the Heart Disease Dataset**
   - **Objective:** Implement a Random Forest algorithm and evaluate it on the heart disease dataset with various numbers of trees and feature subsampling methods.
   - **Steps:**
     - Preprocess the dataset by one-hot encoding categorical variables.
     - Implement Random Forest with different configurations for the number of trees and feature subsampling.
     - Plot the test classification error as a function of the number of trees for various subsampling methods.

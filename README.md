### **Project: Building Linear & Logistic Regression from Scratch**

### Overview
This project involves building, training, and validating two fundamental machine learning models from scratch using only Python and NumPy.
- **Part A:** Linear Regression predicts Boston house prices, demonstrating regression techniques.
- **Part B:** Logistic Regression predicts passenger survival on the Titanic, demonstrating classification techniques.
The goal is to showcase a deep, practical understanding of the core mechanics of these foundational algorithms.

### Key Concepts & Skills Demonstrated
- **Object-Oriented Programming:** Implemented both algorithms in clean, reusable LinearRegression and LogisticRegression classes.

- **Gradient Descent:** Used vectorised gradient descent to optimise model parameters by minimising a cost function.

- **Cost Functions:** Implemented Mean Squared Error (MSE) for linear regression, $J(\theta) = \frac{1}{m} \sum(h_{\theta}(x) - y)^2$, and Log-Loss  for logistic regression.

- **Hypothesis Functions:** Implemented the linear hypothesis $h_{\theta}(x) = \theta^T x$ for regression and the sigmoid hypothesis $h_{\theta}(x) = g(\theta^T x)$ for classification.

- **Data Preprocessing:** Applied feature scaling, handled missing values, and used one-hot encoding for categorical data.

- **Model Validation:** Verified both from-scratch implementations by comparing their performance against the industry-standard Scikit-learn library.

- **NumPy:** Utilised NumPy for all efficient, vectorised mathematical computations.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

### Results

**Part A: Linear Regression** 

The model successfully converged after 2000 iterations. Its performance on the unseen test data was validated against Scikit-learn, with the final Mean Squared Error (MSE) being nearly identical and proving the correctness of the implementation.

| Model                  | Final MSE on Test Set |
| ---------------------- | --------------------- |
| My From-Scratch Model  | **24.69**             |
| Scikit-learn's Model   | **24.29**             |

**Part B: Logistic Regression**

The model successfully converged after 1000 iterations. Its final accuracy on the test set was identical to the Scikit-learn equivalent, validating the implementation.

| Model                  | Final Accuracy on Test Set |
| ---------------------- | -------------------------- |
| My From-Scratch Model  | **81.01%**                 |
| Scikit-learn's Model   | **81.01%**                 |

### How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/matthewmich1/ML_from_scratch.git](https://github.com/matthewmich1/ML_from_scratch.git)
   ```
2. Navigate to the project directory:
   ```bash
   cd ML_from_scratch
   ```
3. Open and run the Jupyter Notebook:
   ```bash
<<<<<<< HEAD
   jupyter notebook "linear_regression.ipynb"
   jupyter notebook "logistic_regression.ipynb"
=======
   jupyter notebook "regression_from_scratch.ipynb"
   jupyter notebook "logistic_regression_from_scratch.ipynb"
>>>>>>> 665aa1949d697274729398ae7987e6798dbeb717
   ```

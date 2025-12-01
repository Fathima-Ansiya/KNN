🌸 Iris Flower Classification – KNN Model

This project applies the K-Nearest Neighbors (KNN) algorithm on the popular Iris dataset to classify iris flowers into three species.

📘 Dataset Description

The Iris dataset contains 150 rows and 4 features:

Feature	Description
Sepal Length	Length of sepal (cm)
Sepal Width	Width of sepal (cm)
Petal Length	Length of petal (cm)
Petal Width	Width of petal (cm)

Target Labels:

Setosa

Versicolor

Virginica

🎯 Project Objective

Build a KNN classifier

Predict the species of a flower

Find the best K value using accuracy

Evaluate the model using confusion matrix and accuracy score

🔧 Steps Performed

Loaded and cleaned the dataset

Dropped unnecessary columns

Split into train and test sets

Scaled the features using StandardScaler

Trained KNN with values of K from 1 to 20

Selected the best K based on accuracy

Visualized confusion matrix

Evaluated performance

📊 Model Evaluation

Accuracy Score

Confusion Matrix

Classification Report

These metrics show how well the model predicts each iris species.

📦 Dependencies
pip install numpy pandas scikit-learn matplotlib

🧪 How to Run

Clone or download the repository

Open the notebook or .py file

Run the script cell-by-cell

View predictions and evaluation results

📝 Conclusion

The KNN model performs well on the Iris dataset due to its simple and well-separated classes.
You can further experiment with:

Changing K values

Trying different distance metrics

Visualizing decision boundaries

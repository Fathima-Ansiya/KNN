🌸 Iris Flower Classification – KNN Model

This project applies the K-Nearest Neighbors (KNN) algorithm on the popular Iris dataset to classify iris flowers into three species based on their measurements.

📘 Dataset Description

The Iris dataset contains 150 rows and 4 features:

Feature	Description
Sepal Length	Length of the sepal (cm)
Sepal Width	Width of the sepal (cm)
Petal Length	Length of the petal (cm)
Petal Width	Width of the petal (cm)

Target Variable:

Setosa

Versicolor

Virginica

🎯 Project Objective

To build a KNN classification model that predicts the species of an iris flower based on its characteristics.

🔧 Steps Performed

Importing the Iris dataset

Exploratory Data Analysis (EDA)

Checking shape, summary statistics

Visualizing distributions

Splitting dataset into train and test

Scaling features using StandardScaler

Training KNN model with different values of k

Finding best k using accuracy comparison

Evaluating model using

Accuracy score

Confusion Matrix


📊 Model Evaluation

The model performance is checked using:

Accuracy Score

Confusion Matrix


These help understand how well the model predicts each class.

📦 Dependencies

Install the required libraries:

pip install numpy pandas scikit-learn matplotlib seaborn

🧪 How to Run

Clone the repo

Open the notebook (.ipynb)

Run all cells step by step

Check predictions and evaluation metrics

📝 Conclusion

KNN performs very well on the Iris dataset due to its small size and clear separation between classes.
You can experiment with:

Different values of k

Distance metrics (euclidean, manhattan)

Train-test split sizes

Visualization of decision boundaries

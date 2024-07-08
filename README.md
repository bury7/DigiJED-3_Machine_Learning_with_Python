# DigiJED-3_Machine_Learning_with_Python

This is a repository for the projects I did on the DigiJED-​3 ICT Machine Learning with Python. The entire course consisted of three main labs. Labs covered topics such as data preprocessing, data classification, and data clustering.

## Overview of the Course
This course is an introduction to Machine Learning. It covers topics like supervised and unsupervised learning and introduces machine learning tasks such as classification, regression, clustering, and dimensionality reduction, along with approaches to evaluating machine learning models. I learned to use the scikit-learn, pandas, and numpy libraries to solve tasks in lab classes.

The course content included an introduction to machine learning and various machine learning tasks such as classification, regression, clustering, and dimensionality reduction. I also covered data preprocessing techniques and models like linear regression and logistic regression. I explored classifiers such as the k-nearest neighbors classifier and decision trees, and learned about metrics for classification and regression tasks. The course also included techniques for evaluating the performance of regression and classification models, as well as algorithms like k-means and agglomerative hierarchical clustering. Additionally, I studied cluster validity measures and approaches to dimensionality reduction. I gained practical skills using pandas and numpy libraries for data preprocessing and the scikit-learn library for solving machine learning tasks.

## [More about the labs](Labs)

- [Preprocessing of data](Labs/Lab_1)

In this laboratory work, I focused on the crucial stage of data preprocessing, which is fundamental for solving machine learning problems. The primary objective was to understand and apply various preprocessing techniques using Python libraries, and prepare the data for subsequent analysis in future laboratory works.

I began by carefully reading the dataset description to identify the types of features and their valid values. This step was essential for understanding the nature of the data and the preprocessing methods required.

The dataset was examined for missing values, inconsistencies, and outliers. Appropriate methods such as filling, removal, or imputation were applied to handle these issues and ensure the dataset's integrity.

Categorical features were encoded into numerical values using techniques like one-hot encoding and label encoding. This step was necessary for making the data suitable for machine learning algorithms that require numerical input.

Quantitative features were normalized and scaled to standardize the data, ensuring that all features contributed equally to the analysis. Techniques such as Min-Max scaling and StandardScaler from scikit-learn were used for this purpose.

Transformations such as log transformation were applied to certain features to stabilize variance and make the data more normally distributed, which is beneficial for many machine learning algorithms.

Overall, this lab work provided me with a comprehensive understanding of the data preprocessing stage. By cleaning, encoding, normalizing, and transforming the data, I prepared it for effective use in machine learning tasks. This foundational step is crucial for ensuring the accuracy and efficiency of any subsequent analysis and modeling efforts.

- [The classification problem](Labs/Lab_2)

In this laboratory work, I focused on implementing and evaluating various machine learning models to achieve accurate data classification. The primary models explored were Logistic Regression, both with and without L1 regularization, and k-Nearest Neighbors (kNN). Process began with data preprocessing, which involved splitting the dataset into training and testing sets and applying necessary transformations to ensure the data was ready for modeling.

I trained multiple models, including standard Logistic Regression, Logistic Regression with L1 regularization, Logistic Regression with L1 regularization and balanced classes, and kNN. Each model was evaluated using cross-validation and validation curves to fine-tune hyperparameters, particularly the 'C' parameter for logistic regression. This step was crucial in identifying the optimal hyperparameter values that would enhance model performance. The evaluation metrics used included balanced accuracy, recall, precision, and confusion matrices, providing a comprehensive understanding of each model's performance.

Comparing the performance of the classifiers on the test set revealed that Logistic Regression with L1 regularization and balanced classes was the most effective model. It achieved the highest balanced accuracy and provided a good balance between precision and recall for both classes. This model demonstrated a strong ability to classify data correctly, highlighting the importance of using balanced classes to improve model performance.

Overall, this laboratory work underscored the significance of hyperparameter tuning and model selection in achieving optimal classification performance. The results demonstrated that Logistic Regression with L1 regularization and balanced classes could effectively minimize both false positives and false negatives, making it a valuable approach for accurate data classification.

- [The clustering problem](Labs/Lab_3)

In this laboratory session, I delved into data clustering to understand how to identify and analyze clusters within a dataset. The work involved several key tasks:

I started by importing necessary libraries and loading the dataset from an Excel file. After cleaning the data, I constructed a scatterplot matrix to visually inspect potential clusters. The scatterplots showed that the data points were evenly distributed, indicating no obvious clusters.

Creating a graph to observe changes in a specific index relative to body temperature for each patient. This helped in visualizing individual variations and understanding the data dynamics better.
        
Applying clustering algorithms like K-Means and Agglomerative Clustering to the dataset. To evaluate the performance of these algorithms, I used metrics such as the Calinski-Harabasz index, Davies-Bouldin index, and Silhouette score.

Overall, this lab work provided valuable hands-on experience in data clustering, from visualization to the application and evaluation of clustering methods. It enhanced my understanding of how to approach and solve clustering problems using Python and scikit-learn.

### Summary

All folders with laboratory works also contain data sets with which I worked.

In order to learn more about laboratory work, you can view the corresponding files, they are available in both English and Ukrainian.

## License

This repository is provided for educational and reference purposes under the MIT License.

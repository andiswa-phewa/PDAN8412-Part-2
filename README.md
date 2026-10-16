# PDAN8412/w Part 2: Predicting Kindle Bestsellers

**Student Number:** ST10123828  
**Student Name:** Andiswa Sibusisiwe Phewa
**Module:** Programming for Data Analytics 2

## About the Project

This project focuses on predicting whether books are likely to be classified as bestsellers using Logistic Regression. It builds on the publishing company scenario introduced in Part 1, where the focus was on identifying authors based on their writing styles.

For Part 2, I used the Amazon Kindle Books Dataset 2023, which contains 133,102 book records. The aim was to explore the characteristics of bestselling and non-bestselling books and develop a classification model using the available data.

## Project Implementation

The analysis involved exploring and cleaning the dataset, identifying relevant features and preparing the data for model training. Apache Spark was used for data analysis, while Python and NumPy were used to develop the Logistic Regression algorithm from scratch.

Different training configurations were tested, and the final model was evaluated using accuracy, precision, recall, F1-score and ROC-AUC. Visualisations were also generated to explain the dataset, training process and model performance.

## Running the Project

To run the project, extract the complete folder and open Anaconda Prompt. Activate the Python environment containing PySpark and the required libraries, then navigate to the project folder and launch Jupyter Notebook.

Open the Part 2 Logistic Regression notebook and select Run All Cells from the Run menu. Once execution is complete, save the notebook to retain the results.

The original dataset must remain in the kindle_data folder. The generated graphs and analysis results are stored in the part2_outputs folder.

## Results and Findings

The dataset contained 2,236 bestselling books, representing approximately 1.68% of the records. This imbalance presented challenges when developing the classification model.

The final model achieved a ROC-AUC score of approximately 0.78, suggesting that it could distinguish between the two classes to some extent. However, the low precision indicated that the model still produced a considerable number of incorrect bestseller predictions.

These findings highlight the importance of evaluating classification models using several performance measures rather than relying on accuracy alone. They also demonstrate the limitations of using historical book listing information to predict future commercial success.

## Dataset Source

asaniczka. 2023. *Amazon Kindle Books Dataset 2023 – 130K Books*. Kaggle.

https://www.kaggle.com/datasets/asaniczka/amazon-kindle-books-dataset-2023-130k-books

The accompanying report contains the detailed analysis, figures, discussion and academic references.

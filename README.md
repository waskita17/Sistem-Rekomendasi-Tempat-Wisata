# Sistem-Rekomendasi-Tempat-Wisata

1. Pre-Processing,
The first step in our research is to process user review data into rating values. This data processing process 
aims to change the form of review data information into rating data. The resulting information is then processed using  
the Cosine Similarity and Singular Value Decomposition methods. The steps in the pre-processing process are 
eliminating stop words and conducting analysis to get the rating value.

2. Cosine Similarity, 
The similarity value between items is calculated using the calculation of the cosine angle value of two variables 
or vectors. By comparing each vector and given a predicted rank based on the cosine similarity for each category.
The Matrix Factorization technique aims to test the training data to calculate the matrix values that have adjacent 
similarity values. The matrix value based on factorization is concluded to get a ranking pattern.

3. Singular Value Decomposition,
The first stage in this method is dividing the data into two. The distribution of data is 80% training data and 20% 
testing data. The greater the amount of training data used can affect the value of the output data testing. The process 
in the Singular Value Decomposition method, the process that needs to be done is Tuning hyperparameters as well 
as modeling using existing train data and testing the designed model to the test data. After doing data splitting, then the data is processed to be carried out for modeling. Python surprise library has provided Singular Value Decomposition function. Surprise is useful in data exploration processes that require fast 
time to generate predictions.

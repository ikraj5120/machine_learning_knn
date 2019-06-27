# machine_learning_knn
KNN implemenation for Iris dataset

download rewuired packages from requirement file using below command:
pip install -r requirements.txt


Steps:
1. import libraries and useful tools
2. load iris dataset from sklearn and convert to a DataFrame
3. Decide training and testing features
4. transform species values in numbers
5. divide dataset into training and testing set based on the test_size
6. Scale your dataset in standand units
7. for values of K from 1 to 20 find the mean square root errors and append in a list
8. plot error values, from previous plot , choose the value of K such that sqaure root mean error is minimum
9. fit the KNN Classifier with this valus of K and predict values
10. Test your results

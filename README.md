# Would-you-survive-a-titanic-disaster?
This Machine Learning project is based on the famous titanic disaster 

The dataset that I have chosen to work on for this Machine learning project is the famous <b>Titanic dataset</b>. The question “Could you survive the Titanic?” is one of the most intriguing question. Machine Learning may help you find out. This is a report on the open titanic dataset in which it contains the passenger details who went on a voyage in titanic. With the help of various attributes such as class, age, sex, ticket, fare etc., we will build models and experiment with various machine learning algorithms. 

<b>Required Packages:</b>

I have imported various packages like matplotlib, numpy, random, pandas. I have also imported some from the scikit- learn packages(sklearn) like datasets, svm, cross_validation, tree,  preprocessing and metrics. Some machine learning algorithms to perform machine learning tasks for Logistic Regression, SVC, Random forest classifier, k neighbour classifier and Gaussian NB.

<b> Children-Women first:</b>

The grouping is done by the age on the x axis and on the y axis the survival rate is plotted. The X axis ranges from 0 to 90 with a cut of 10 units in between i.e., 0-10, 10-20 …. 80-90. 

<b>Creating a datafreme, pre processing training and testing sets:</b>

Now I have created a dataframe with body, cabin and boat attributes. After that cleaning the data i.e., removing the sets which have “NA” values in them. Standardization of dataset is important to perform the machine learning algorithms hence we perform pre processing before running the algorithms. Now creating the training sets and testing sets for running the algorithms with the help of variable X and Y.

## Performing Machine Learning techniques:
<b>Logistic Regression:</b>

Logistic regression is used with the data which there is a binary output. Although there are other cases where the dependent variable is of more than two cases which are called multinomial regression. Logistic regression makes no assumption about the independent variables. When performed the logistic regression on the titanic dataset its output was 0.78493150684931512 . The MSE and RMSE values are 0.0054 and 0.0518

<b>Gaussian Naive Bayes:</b>

Gaussian Naive Bayes is one of the Naïve Bayes algorithm. Naïve Bayes uses posterior probability for each class to classify. It is easy and fast to predict class of dataset.  In Gaussian Naïve Bayes the features follow normal distribution. Here we apply the Gaussian Naive Bayes from sklearn package on our training and testing dataset. The output is 0.76986301369863008

<b>Decision Tree:</b>

In order to perform this we start with making an instance and fit the classifier to the training set we created. The output is 0.7539936102236422. The precision and recall scores are 0.007 and 0.086

<b>Random Forest:</b>

Usually random forest classifier creates very poor trees for dataset using random subsets of input variables and return the prediction which is returned by most of the trees. The output is 0.97671232876712333

<b>Knn:</b>

Knn is non parametric method used for classification and regression. Output is a class membership. For this I have set the k = 4 which is nearest neighbor.  The output is 0.77534246575342469

<b>Support vector machines:</b>

A SVM is discriminative classifier formally defined by separating hyperplane. The operation of the SVM algorithm is based on finding the hyperplane that gives the largest minimum distance to the training examples. The output for this dataset is 0.89726027397260277

## Conclusion:
This is a glance of Machine Learning in Python that I have worked on for this project. I hope you have understood this report as I tried to explain clearly to the best of my knowledge. 

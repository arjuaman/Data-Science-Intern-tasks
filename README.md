# Data Science Internship tasks by The Sparks Foundation, Singapore

## Task 1

### Objective : LinkedIn profile modifications
 
-> https://linkedin.com/in/arjuaman

## Task 2

### Objective : To Explore Supervised Machine Learning

In this regression task we will predict the percentage of marks that a student is expected to score based upon the number of hours they studied. This is a simple linear regression task as it involves just two variables.
Data can be found at http://bit.ly/w-data </br>
<strong>Question:</strong> What will be predicted score if a student study for 9.25 hrs in a day? </br>

<strong>Answer:</strong> After analyzing the data and breaking in into train-test split, and plotting, we can the linear pattern:</br>
![alt_text](https://github.com/arjuaman/Data-Science-Intern-tasks-by-The-Sparks-Foundation/blob/master/Task_2/tr_.png)

![alt_text](https://github.com/arjuaman/Data-Science-Intern-tasks-by-The-Sparks-Foundation/blob/master/Task_2/tr_sc.png)

Upon doing the EDA and training on all the training data, we have: </br>
![alt_text}(https://github.com/arjuaman/Data-Science-Intern-tasks-by-The-Sparks-Foundation/blob/master/Task_2/all_data.png)

Hence, If a student studies for 9.25 hours a day, percentage he'd score: 95.35 %

## Task 3

### Objective : To Explore Unsupervised Machine Learning

<strong>Question:</strong> From the given ‘Iris’ dataset, predict the optimum number of clusters and represent it visually.
Dataset : https://drive.google.com/file/d/11Iq7YvbWZbt8VXjfm06brx6 6b10YiwK-/view?usp=sharing </br>

<strong>Answer:</strong> Upon doing the EDA we can see from the dataset that: </br>
![alt_text](https://github.com/arjuaman/Data-Science-Intern-tasks-by-The-Sparks-Foundation/blob/master/Task_3/df_rep.png)

On further cleaning and outputing the target variables as a function of features: </br>
![alt_text](https://github.com/arjuaman/Data-Science-Intern-tasks-by-The-Sparks-Foundation/blob/master/Task_3/easy_sight.png)

Now, to find the optimum number of clusters, we use the elbow method.</br>
![alt_text](https://github.com/arjuaman/Data-Science-Intern-tasks-by-The-Sparks-Foundation/blob/master/Task_3/elbow.png)

So we can see that the optimum number of clusters is 3, hence we do the final clustering: </br>
![alt_text](https://github.com/arjuaman/Data-Science-Intern-tasks-by-The-Sparks-Foundation/blob/master/Task_3/final_rep.png)

## Task 4

### Objective : To Explore Decision Tree Algorithm

<strong>Question:</strong> For the given ‘Iris’ dataset, create the Decision Tree classifier and visualize it graphically. 
The purpose is if we feed any new data to this classifier, it would be able to predict the right class accordingly.

<strong>Answer:</strong> With the EDA already done in Task 3, I created a Decision Tree Classifier: </br>
![alt_text](https://github.com/arjuaman/Data-Science-Intern-tasks-by-The-Sparks-Foundation/blob/master/Task_4/drugtree%20(1).png)

It predicted 'Iris-versicolor' when given the mean of features as input, which is correct as can de seen from the EDA part,i.e. 2nd figure of Task 3.


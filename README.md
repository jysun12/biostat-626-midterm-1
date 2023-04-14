# biostat-626-midterm-1
# Task 1-data processing
We import the dataset we used and we need to do the data processing. Also, we can use “set.seed()” function to ensures the same sequence of random numbers generated in the different runs of the code. For here, I used “set.seed(123)”. 
we need to build a binary classifier to classify the activity of each time window into static (0) and dynamic (1). According to the requirement, I made a new variable  ”if_dynamic" to identify which activity is static. In my view, activity 1,2,3 are the dynamic ones. The others are static. So, we need to set the level for this categorical variable ”if_dynamic”.
# Task 1-split the dtata set
Next, we need to split the data as training and testing set. I used the function” createDataPartition” and set P=0.8 to split the training data as 8:2. Besides, I also check the distribution in original data and partitioned data and preprocess.
# Task 1-Algorithims and result
In addition, I use Logistic Model, LDA, SVM Linear and SVM Radial to see the performance based on the training data and predict the “activity” in the” test_data”. We will receive a result that need to be submitted.
# Task2-data processing
we need to build a refined multi-class classifier to classify walking (1), walking_upstairs (2), walking_downstairs (3), sitting (4), standing (5), lying (6), and static postural transition (7). 
I used levels functions to set activity = 8,9,,10,11,12 as 7 and set activity as a categorical variable.  And keep walking as 1, walking_upstairs as 2, walking_downstairs as 3. 
# Task 2-split the data set
Next, we need to split the data as training and testing set. I used the function” createDataPartition” and set P=0.8 to split the training data as 8:2. Besides, I also check the distribution in original data and partitioned data and preprocess.
# Task 2-Algorithims and result
In addition, I used LDA, SVM Linear and SVM Radial to see the performance based on the training data and predict the “activity” in the” test_data”. We will receive a result that need to be submitted.

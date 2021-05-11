# Predicting-Trends-in-Quality-Oriented-Jobs
This project has been created to study the requirements of quality oriented jobs that are available in the market and predict the salaries in the mentioned fields. This model will help students to study the market and choose their careers and necessary factors to get the job. Different machine learning models are tried and their accuracy is checked.

The data visualisation and Machine learning models are trained and tested to predict if the candidate get the job and approximate the salary for their part. The results will be based on SSC percentage, SSC Board, HSC percentage, HSC Board, HSC Stream, Degree type(UG Degree), Degree percentage, Work experience, employability, PG MBA specialisation and percentage and gender.

The dataset has almost new missing values are present, and all those are treated with filling it medians. The dataset consists of the above mentioned features. The dataset has been divided as 70%-30%. 70% data is used for training and 30% data is used for testing. The testing data is used for chacking the accuracy of the model.

The algorithms used are:
	For Placement prediction:
		1. Decision Tree (Accuracy score=83% )
		2. Gaussian Naive-Bayes (Accuarcy score=89.15%)
		3. Gradient Boosting Classifier (Accuracy score=86.15%)
	For Salary prediction:
		1. Decision Tree (Accuracy score=30.77% )
		2. Gaussian Naive-Bayes (Accuarcy score=27.69%)
		3. Gradient Boosting Classifier (Accuracy score=30.77%)
		4. Support Vector Machine (Accuracy score=36.92%)
		5. K-Neighbour Classifier (Accuracy score=38.46%)

The features of the dataset are mentioned below:
1. sl_no => Serial number
2. gender => Male or Female 
3. ssc_p => Percentage in 10th grade 
4. ssc_b => Board of 10th grade
5. hsc_p =>Percentage in 1th grade
6. hsc_b => Board in 12th grade
7. hsc_s => Stream in 12th grade
8. degree_p =>Percentage in degree
9. degree_t => Degree type (Sci&Tech or Comm&Mgmt)
10. wrokex => Work Experience
11. etest_p => Employability Test percentage
12. specialisation => PG MBA specialisation
13. mba_p => MBA precentage

This project is made for Orion E-Hackathon 2021 by:
Abhilasha Deshmukh
Shruti Dalvi
Nayana Dutargi

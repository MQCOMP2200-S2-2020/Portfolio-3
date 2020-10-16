# Portfolio-3
This repository will hold your portfolio projects for this semester. You should customise this README.md file to document your own work - add your name and details and describe what you've done. This will be displayed on your Github page.

Name: Md Noor Islam Amil ID#45688249

The goal of the second portfolio is to reproduce some work on predicting the energy usage of a house based on Internet of Things (IoT) measurements of temperature and humidity and weather observations.

This portfolio will reproduce the initial results of the target research paper to be found in the link: Data driven prediction models of energy use of appliances in a low-energy house. Luis M. Candanedo, Véronique Feldheim, Dominique Deramaix. Energy and Buildings, Volume 140, 1 April 2017, Pages 81-97, ISSN 0378-7788, http://dx.doi.org/10.1016/j.enbuild.2017.01.083. The concrete goals to acheive for this portfolio are decribed below:

An exploration of the data showing the distribution of values of variables that matches some of the plots shown in the first part of the paper. 

Fitting a linear model to the data and generating evaluation metrics (mean squared error, R2) 

Use the sklearn RFE function to apply Recursive Feature Estimation to the data to select the best features, compare with the results described in the paper for the same operation. Compare your results with those in the paper.

The portfolio starts by using data preparation to conform the dataset with the desired characteristics as suited for my analysis. The dataset was imported and its achracteistics checked in the code to find any missing items or values that needed to be fixed. I also made sure that all book entries were categorized with at least one genre. 


The feature extraxtion step begins with the simple count of words, sentences and characters. I then tried to associate it with the genre to find commonalities for surther investigation. I have used word count as basis of the feature extraction algorithm. Then I tried to train the model using the word count as a means of popularity against the genre. Therefore, my intention is to use common words that typically found in certain genres to be used as the guideline in detcting and thus assigning genres in the test case. 

The initial model training proceeded smoothly and I was able to use Logistic Regression analysis to plot multiple plots. These graph plots show the various distribution of genres assigned to the test case in different runs. The runs show significant differences in clustering the distribution od assigned genres of the test case. This shows the fluctuating accuracy even though the training set remains the same and produce consistent results.

The Model Evaluation step discusses the accuracy of the predictive model by calculating the calssification report. I have used the accuracy, precision, recall as factors to estimate the effectiveness of the predictive model and performed Logistic Regression, Support Vector Machine, Decision Tree Classifier, K-Nearest Neighbor Analysis, Linear Discriminant Alaysis and Gausian Analysis to gauge the ROC of the training and test cases.

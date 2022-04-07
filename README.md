# Titanic-


## The challenge¶
The competition is simple: we want you to use the Titanic passenger data (name, age, price of ticket, etc) to try to predict who will survive and who will die.

![surviving.jpg](attachment:surviving.jpg)


This serves as the beginner project as I kick off my Data Science Career I hope to look back on this particular project and laugh at how easy it will be to do in the future. However, this is step one a lot more projects to go!! 


Thank You for tuning in to my  notebook 



## Data Preprocessing
Drop null values

Include only relevant variables(since we have limited data I want to exclude things like name and passsenger ID so that we could have a reasonable number of features

do categorical transforms on all data . Usually we would use a transformer, but with this approach w can ensure that our training and test data have the same columns. We also may be able to infer somthing about the shape of the test data through this method.

impute data with mean for fare and age

normalized fare logarithm to give more semblancee of a normal distrubutio

scaled data 0-1 with standard scale

![Data Exploring]("C:\Users\metropolitanparkapts\Desktop\AAAA.JPG")



## Conclusion
As I am picking the best model based upon how well the model is performing on the training data. with no feature scaling or anything of that nature and the model with the best score is the decision tree model.

This mode performed with 83.73 identifiable variance. Correctly predicting who survived and who did not.

Future Changes
As this is a beginner project simply to measure my growth in code there are several things I will change in the future.

I will experiment with the features a bit more Run a grid search for our models to hypertune parameters Hyper tune my cross val score as well. I will be Actually expanding upon my baseline model focusing on the accuracy of the model.

Most credit on this project goes to these two youtubers.

Ken Jee

The Indian Developer
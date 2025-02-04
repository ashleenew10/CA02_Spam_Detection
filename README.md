# CA02_Spam_Detection
The purpose of this program is for training a ML model with a set of emails labelled as spam or not spam to classify future emails accordingly.

### The data I am using has been provided by an LMU professor in an Intro to ML MSBA course. Within this repository, I have included a  file included called "CA02_NB_Assignment" that I referenced to complete the CA02 assignment.

## Prior to running the code please ensure the following:
* Dowload the zip file "Data.zip" that includes folders called "test-mails" and "train-mails" (test emails and training emails).
* Make sure that you are using the relative path names of the data folder locations based on which folder they are located on on your computer (ex: "./train-mails").
* The folder where you are holding the email files should also be where your .ipynb file is located.
* Install all required packages (see those used at top of python file).

__In addition to these notes, there are three different models that are looked at within this code located under the section titled "Training our model using Naive Bayes algorithm":__
* model = GaussianNB()
* model = MultinomialNB()
* model = BernoulliNB()

_Comment out 2 of the 3 at any given run to make sure you are only using one approach at a time_


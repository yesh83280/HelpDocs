# Steps to implement ML Model

1. Understand the problem
2. Prioritise the factors that impact the output
3. Prepare & Collect dataset
4. Clean & Process the dataset (Null Values, Duplicate, Irrelevant)
5. Choose the appropriate ML Algorithm and Train the model
6. Evaluate the model - Accuracy, Confusion Matrix - Check Graphs  
7. Analyse the model and retrain the models with different ML algorithms
8. Deploy the model and Predict using ML Model

# Steps to apply in ML Model for PO and NonPO - 

1. Gather Dataset
2. Perform Exploratory data analysis - Cleaning, preprocessing, analysing
3. Apply NLP to convert text formatted data to categorical data - Raw text (sentences) into vectors (words)
4. Apply classification algorithm on Categorical data to predict classificaition
5. Analyse the result and reiterate the flow.

Applied EDA - 

1. Noticed duplicates in the dataset - Removed them by subset of [‘Subject','Label'] 
2. No Null Values found 
3. Plotting Pie chart for count of each category - Looks like more count of Non PO 
4. Checking whether Length matters in finding PO or Non PO - Doesn’t impact
5. Processing Text :
    1. Remove all stopwords and numbers
    2. Modifying non meaningful words like PO to 'Purchase Order', Re: to 'Reply:'
    3. Replace all special characters other than a-z, A-Z, 0-9 and Special Characters like space
    4. Adding data back by converting to Lower case - Case Sensitive
6. Noticed only to apply Lemmatising and not stemming since its changing the meaning of the word like its considering Purchasing and Purchase as 2 separate entities. 
7. Used picturing important concepts using WordCloud
8. Finding wide variety of words combination using ngram concept - 1,2

PO & Non PO Classification Steps

1. Analysed the dataset 
    1. Noticed duplicates - Combination of Subject and Label - Same subject has multiple labels as PO and NonPO
    2. Remove special characters / punctuations / numbers / irrelevant words 
    3. Need to remove Stop Words
2. Cleaning the data 
    1. Remove duplicates or empty values
3. Applying NLP on text formatted data 
    1. Applying Bag of words approach - Extracting unique word in a text will be represented by one number
    2. Need to decide how to do Normalisation
        1. Preforming Pre-Processing Text - Removing special characters, punctuations, stop words, numbers
        2. Check whether to apply or not to apply Stemming/Lemmatizing on data set
        3. Need to try with different values for N-Gram size
        4. Need to check whether to apply POS or not 
    3. Applying Feature Engineering - Using Bag Of Words
        1. Calculate Term Frequency - Build CountVectorizer - Converting Lemmas into vector  boolean case of True or False
        2. Calculating Integer counts to TF-IDF scores - tfidftransformer
4. Passing on Categorical output of NLP which is TF-IDF Vectors to any classification algorithm - Naive Bayes or SVM or XGBoost or Random Forest
5.  Model Evaluation - Determining how well our model did overall on the entire dataset.


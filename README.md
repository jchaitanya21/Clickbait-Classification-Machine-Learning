# Title: Clickbait Classification using Machine Learning

## Descriptions:

Clickbait is content that is posted on the websites and whose main goal is to encourage the user to click on the link to a particular web page. Advertisement specifies announcements made by various brands related to their products to the open public. Advertisements are done on various platforms such as newspapers, television radio among them the most common and geographical best sources are websites. Website once hosted is accessed by large scale audience from diverse areas. Clickbait is a very imaginative way to attract users to click on the content which is an advertisement related to products.
This clickbait can have some downfalls as well, anonymous people can use clickbait to give misleading information about the products of the company and can ultimately damage the overall brand status and can lead to companies losing their customers. Clickbait constructively used for getting more views on the pages. More people clicking on an advertisement and sharing them to various social media platforms ultimately achieve the main objective of the companies, that their product is reached to a more and more potential customer but ultimately destructively it is used to mislead the people about the product.
Often we get bombarded with these non-relevant ads/pop ups whenever we try to access a particular webpage or whenever we are surfing on the browser. The content whose main purpose is to attract attention and encourage visitors to click on a link/image to a particular web page in order to generate advertising revenues.This model identifies the text of advertisements/pop-ups or hyperlinks like this of sorts whether it is spam/malicious or not.

## Cover Points

1.	The problem is binary classification whether the text data is clickbait or not

2.	The clickbait comprised 32000 records with a 50:50 ratio of both classes of data (clickbait text and not clickbait text).

3.	In this dataset, binary categories are

    a.	0  Not Clickbait Headline

    b.	1  Its Clickbait Headline

Dataset Link: https://www.kaggle.com/amananandrai/clickbait-dataset

## Procedure:

1.	Data is uploaded on Google Drive.

2.	Data is viewed in a dataframe using pandas dataframe.

3.	Data Preprocessing: Data processing is important in terms of textual data or unstructured data. Data Preprocessing or Cleaning is the process of removing unnecessary symbols, articles from text to make it easy for machine learning models to make better predictions.

4.	The stopwords, digits, non alphanumerics, data fall under noise for Machine Learning estimators

5.	Tokenization

6.	Stemming

7.	Lemmatization

8.	Stopwords are removed

9.	Tokens are converted into vectors via Tf Idf (Term Frequency Inverse Document Frequency) over Countvectorizer

10.	The model is trained on Data after its lemmatized and stop words are removed.

11.	4 Machine Learning Estimators/ Models are used
    
    a. Logistic Regression
    
    b. Random Forest Classifier 
    
    c. Support Vector Machine 
    
    d. Naive Bayes
    
12.	Evaluation Metrics used.
    
    a. Accuracy
    
    b. Classification Report
    
    c. Confusion Matrix.

## Tools/Technologies/Algorithms

1. Front-End: Python Programming Language

2. Back-End: CSV Files (Comma Separated Values)

3. Hardware: Not Applicable

4. Libraries: Pandas, Numpy, Sckit Learn, NLTK, Matplotlib.

5. Problem Domain: Natural Language Processing

6. Problem Type: Binary Categorical Classification (Supervised Learning) 

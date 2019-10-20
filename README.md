# TextAnalysisDWM
DWM project of CE Department 2019
# Overview
Following is the DWM Project implemented by the 5th Sem CE Department of IIIT Bhubaneswar.

## Features implemented:

* **Data Cleaning**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/spam1.PNG)
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/spam2.PNG)
* **Tokenisation**

Tokenization relies mostly on simple heuristics in order to separate tokens by following a few steps:

    Tokens or words are separated by whitespace, punctuation marks or line breaks
    White space or punctuation marks may or may not be included depending on the need
    All characters within contiguous strings are part of the token. Tokens can be made up of all alpha characters, alphanumeric characters          or numeric characters only.

Tokens themselves can also be separators. For example, in most programming languages, identifiers can be placed together with arithmetic operators without white spaces. Although it seems that this would appear as a single word or token, the grammar of the language actually considers the mathematical operator (a token) as a separator, so even when multiple tokens are bunched up together, they can still be separated via the mathematical operator.

* **Stemming**\

![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/stopWords.PNG)
* **Data Wrangling and Pre-processing** 

**Data preprocessing**
Data Preprocessing is a technique that is used to convert the raw data into a clean data set. In other words, whenever the data is gathered from different sources it is collected in raw format which is not feasible for the analysis.

Therefore, certain steps are executed to convert the data into a small clean data set. This technique is performed before the execution of Iterative Analysis. The set of steps is known as Data Preprocessing. It includes –

    Data Cleaning
    Data Integration
    Data Transformation
    Data Reduction
    
 **Data wrangling**
Data Wrangling is a technique that is executed at the time of making an interactive model. In other words, it is used to convert the raw data into the format that is convenient for the consumption of data.

This technique is also known as Data Munging. This method also follows certain steps such as after extracting the data from different data sources, sorting of data using certain algorithm is performed, decompose the data into a different structured format and finally store the data into another database.
Need of Data Wrangling

Data Wrangling is an important aspect of implementing the model. Therefore, data is converted to the proper feasible format before applying any model to it. By performing filtering, grouping and selecting appropriate data accuracy and performance of the model could be increased.

Another concept is that when time-series data has to be handled every algorithm is executed with different aspects. Therefore Data Wrangling is used to convert the time series data into the required format of the applied model. In simpler words, the complex data is transformed into a usable format for performing analysis on it. 

* **Creation of Term-incidence Matrix**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/termIncidenceMatrix.PNG)
* **Creation of Tf-Idf Matrix**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/tf-idfMatrix2.PNG)
* **Implementation of n-grams**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/bi_gramMatrix.PNG)
* **Creation of Cosine similarity on the vector space.**

Cosine similarity is a metric used to determine how similar the documents are irrespective of their size.

Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. In this context, the two vectors I am talking about are arrays containing the word counts of two documents.

As a similarity metric, how does cosine similarity differ from the number of common words?

When plotted on a multi-dimensional space, where each dimension corresponds to a word in the document, the cosine similarity captures the orientation (the angle) of the documents and not the magnitude. If you want the magnitude, compute the Euclidean distance instead.

The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance because of the size (like, the word ‘cricket’ appeared 50 times in one document and 10 times in another) they could still have a smaller angle between them. Smaller the angle, higher the similarity.

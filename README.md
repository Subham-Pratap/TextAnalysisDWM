# TextAnalysisDWM
DWM project of CE Department 2019
# Overview
Following is the DWM Project implemented by the 5th Sem CSE Department of IIIT Bhubaneswar.

## Features implemented:

* **Data Cleaning**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/spam1.PNG)
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/spam2.PNG)
* **Tokenisation**\

Tokenization relies mostly on simple heuristics in order to separate tokens by following a few steps:

    Tokens or words are separated by whitespace, punctuation marks or line breaks
    White space or punctuation marks may or may not be included depending on the need
    All characters within contiguous strings are part of the token. Tokens can be made up of all alpha characters, alphanumeric characters or numeric characters only.

Tokens themselves can also be separators. For example, in most programming languages, identifiers can be placed together with arithmetic operators without white spaces. Although it seems that this would appear as a single word or token, the grammar of the language actually considers the mathematical operator (a token) as a separator, so even when multiple tokens are bunched up together, they can still be separated via the mathematical operator.

* **Stemming**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/stopWords.PNG)
* **Data Wrangling and Pre-processing** 
* **Creation of Term-incidence Matrix**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/termIncidenceMatrix.PNG)
* **Creation of Tf-Idf Matrix**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/tf-idfMatrix2.PNG)
* **Implementation of n-grams**\
![alt text](https://github.com/Rhymester/TextAnalysisDWM/blob/master/Images/bi_gramMatrix.PNG)
* **Creation of Cosine similarity on the vector space.** 

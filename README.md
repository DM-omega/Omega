# Real or Not? NLP with Disaster Tweets
## Team Omega
Maxime Dubi

Kamila Mananova

Bleron Ramaj

## 📑Project description 
Real or Not? NLP with Disaster Tweets: For this project we are challenged to buil a Machine Learning model that can predict which tweets are about a real disaster (1) and which are not (0). 

## 📊 Data 
There is two datasets:
  df_train where we have 6471 rows and five columns.
  df_test where we have to applied our models to predict the "target" column
  
## 🎯 Project structure
**Preparation**
Create new GitHub repository

Create python notebook with Colab

We did an Eda to see what we need to preprocessing

  Merged the keywords with the text
  
  
  Clean the data
  
    Delete the links
    
    Upper case to lower case
    
    Delete unnecessary symbols: @, #,...
    
    
    
  Tokenizer (spacy tokenizer )
  
    Lemmatize
    
    Ponctuation
    
    Remove numbers
    
    Remove stopwords
    


## 🧾 Results and solution

### Best model

TF-IDF Vectorizer with Logistic

Regression

  Max_df = 0.725
  
  Min_df = 0.0
  
  Ngram_range = (1,1)
  
  Smooth_idf = False
  
**Without train_test_split

**Classifier:** Logisitic regression

**Parameters:** C = 2, ngram_range = (1,1), norm = 'l2'

**Accuracy:** 0.821


### Other models

## 📽️ Our video 

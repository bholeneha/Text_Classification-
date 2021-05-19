# Text_Classification-
# Segment#1
## Problem to Solve
Perform text classification on email data and categorize data into four categaries; crime, politics, entertainment and science. This problem falls under "Topic Modelling".

### Rationale for Topic 
Text classification has wide variety of applications in various domains. It can be used in cyber security for classification of doccuments on the basis of privacy and confideniality. It can be used for sentiment analysis for customer reviews in on line shopping etc. 

### Team Members
Fatima Hussain- Model development and technology selection

## Machine Learning Model 
We intend to perform text classification and use Latent Dirichlet Allocation algorithm.
It is an exploratory process and LDA identifies the hidden topic structures in text documents.  It uses Bayesian statistics and Dirichlet distributions for processing and identifyimg the topics.

We may consider using the following classification algorithm, alogwith LDA:
* KNN
* Logitic Regression


### Data Preprocessing
Prior to text classification,  LDA  pre-process the raw text/doccument.

* Normalization: Transform text to normal/canonical form
* Stemming: Reduce a word to its word stem/root without suffixes and prefixes 
* Stopwordremoval: Remove words that do not add any logical meaning 
* Lemmatization:  Words in third person are changed to first person and verbs in past and future tenses are changed into present.
* Tokenization: Break text into ‘tokens’, i.e. words and phrases . Split the text into sentences and the sentences into words. Lowercase the words and remove punctuation.

# Segment#2
## Machine Learning Model 
We performed data cleaning before applying LDA model, and performed following steps:

*  Raw data was available in txt files and we created  data frame for all the data and stored in the google COLAB.
*  Stop words are removed and data is lemanized and tokanized. imported "stopwords" from nltk.corpus ,  "WordPunctTokenizer" from nltk.tokanize, "punctuation" from string, and WordNetLemmatizer from nltk.stem 
* Cleaned data is stored in the same dataframe with column name "Filtered Text"
* 



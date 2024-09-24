# Evaluation of the Effectiveness of Classification Models for HAM and SPAM Identification

This repository contains my Final Degree Project (TFG) of the Applied Statistics degree at the Universitat Autònoma de Barcelona (UAB). The project focuses on the evaluation of the effectiveness of several classification models in the detection of SPAM and HAM emails.

## Project Description
The aim of this work is to analyse a set of 33,716 emails, classified as SPAM or HAM, and to evaluate the performance of several text classification models. In order to optimise the results and reduce the computational cost, an exhaustive pre-processing of the texts has been performed and embeddings have been used.

### Models Used
 - Naive Bayes
 - XGBoost
 - Bidirectional LSTM
 - BERT
   
### Technologies and Tools
 - Python for model implementation and data pre-processing.
 - Numpy, Pandas and Scikit-learn for data manipulation and model evaluation.
 - NLTK and SpaCy for text processing.
 - TensorFlow and Keras for neural network development.
 - Embeddings of Word2Vec and BERT to improve the semantic representation of texts.
   
### Data pre-processing
Text pre-processing has been key to improving model performance and reducing computational complexity. Techniques used include:

 - Text cleaning: removal of special characters, case normalisation, and removal of irrelevant words (stopwords).
 - Tokenisation and lemmatisation to structure texts.
 - Application of embeddings to transform texts into numerical vectors that can be used by classification models.

### Model evaluation
Each model has been evaluated using classification metrics such as:

 - Accuracy
 - Accuracy (Precision)
 - Recall
 - F1-score

### Results
Overall, the BERT-based model showed the best ability to correctly identify SPAM and HAM mails, closely followed by the Bidirectional LSTM model. The Naive Bayes model, although simpler, provided reasonable results with lower computational cost, making it a suitable choice for resource-constrained applications.

# Contact us
For any questions or interest in the project, you can contact me through my [LinkedIn](https://www.linkedin.com/in/arnau-urbina-lopez/) profile.

# Module 6 Knowledge Check

1. **What is term frequency—inverse document frequency (TF-IDF) used for?**
    - [ ] To eliminate topics from a dataset
    - [x] To determine the most commonly used topics in a collection of documents
    - [ ] To extract a list of topics
    - [ ] To perform a classification of topics

2. **Why should lemmatization be performed on a group of topics before extracting common terms?**
    - [ ] To reduce the number of categories
    - [x] To reduce the number of vectors
    - [ ] To determine the accuracy of the model
    - [ ] To make the model more generic

3. **Which option describes the contents of the topic-terms.csv file that an Amazon Comprehend topic modeling job generates?**
    - [x] Lists the top ten words for each topic and the weights for those terms in the topic
    - [ ] Lists the documents that are associated with a topic
    - [ ] Shows the confidence that a document contains a topic
    - [ ] Lists the names of all of the topics

4. **What is Latent Dirichlet Allocation (LDA)?**
    - [ ] A supervised learning algorithm that is available in Amazon Comprehend
    - [x] An unsupervised learning algorithm that is available in Amazon SageMaker
    - [ ] A method for matching topics with a specified set of terms
    - [ ] A method to find the most common term in a document

5. **What is perplexity?**
    - [ ] A metric that indicates the likelihood that terms within a topic are related to each other
    - [ ] A metric that measures the accuracy of a predicted match between a topic and a document
    - [x] A metric that indicates the likelihood that a topic is included in a document
    - [ ] A metric for the overall efficiency of a model that is used for topic analysis

6. **Which statement is the best description of the difference between a Latent Dirichlet Allocation (LDA) model and a Neural Topic Model (NTM) model?**
    - [ ] An LDA model is unsupervised, but an NTM model is supervised.
    - [x] LDA measures the likelihood that the model describes the test data, and NTM measures the similarity of words in a document.
    - [ ] For an LDA model, you specify the topics before training. For an NTM model, you don't specify the topics before training.
    - [ ] LDA supports both GPU and CPU instance types, but NTM supports only single CPUs.

7. **A developer has created a new fraud detection service and needs to quickly build a proof of concept for a feature that groups transactions by purchase type. What is a good reason to select Amazon Comprehend to build the proof of concept?**
    - [ ] Amazon Comprehend is better at developing fine-tuned categories.
    - [x] With Amazon Comprehend, you can build the proof of concept quickly.
    - [ ] With Amazon Comprehend, you can do more preprocessing of the data.
    - [ ] Amazon Comprehend provides more information for data processing audits.

8. **A developer works for an online retail company that offers customers the ability to provide product reviews. Which option would be the best to quickly determine whether any of the reviews are offensive?**
    - [ ] Use a Python library to build a segmentation model of the reviews.
    - [ ] Build a model based on the Neural Topic Model (NTM) algorithm to group topics as offensive.
    - [ ] Extract the text into a database and query for offensive terms.
    - [x] Use Amazon Comprehend to extract key terms that might be offensive.

9. **When comparing two models, the model with the lower coherence score is more likely to group similar topics together.**
    - [ ] True
    - [x] False

10. **A developer used Amazon Comprehend to group customer feedback for the different services that a bank offers. The topic-terms.csv output from this job lists the term "checking" with a weight of 0.08. What does the 0.08 value represent?**
    - [ ] Eight percent of the customers have a checking account.
    - [ ] Eight percent of the words in the feedback collection are "checking."
    - [x] The probability is eight percent that "checking" is one of the top ten words.
    - [ ] The probability is eight percent that a customer has a checking account.

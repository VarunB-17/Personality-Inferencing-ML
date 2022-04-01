# Inferring Personality Type from social media posts
A machine learning project where the main objective was to develop a method to infer one's personality type

         * Sk-learn -----> Developing the Logistic Regression classifier
         * NLTK ---> Pre-processing of data
         * Gensim -> Library for word embedding
         * Pandas ---> Loading data as a pandas dataframe
This is a univerity project done by students from the Vrije Universiteit :

         * Varun Behari
         * Lorenzo Baracco
         * Agostino Sorbo
         * Altan Michelagnoli
         * Illia Vasko
## A scientific paper has been written to clarify all of the decisions decisions made:
The paper presents the performance of state-of-the-art Machine Learning (ML) classification models,
such as K-Nearest Neighbours (KNN) and Logistic Regression, 
on an extended personality Myers Briggs Type Indicator (MBTI) Kaggle dataset. 
Each instance in the dataset consists of a Reddit user's post from the r/mbti subreddit with the labeled personality type. 
The paper investigates into the possibility of using the Doc2Vec word embedding technology to guess an individual's personality type based on their social media posts. By comparing different classification methods, 
the accuracy of the model is evaluated. 
It is concluded that it is indeed possible to use word embedding to classify the personality type of an individual based on their social media posts.

## Dataset
The chosen dataset consists of ~106K records of posts and their authors' personality types. All of the instance are equal-sized: 500 words per sample. In total there are 16 different classes corresponding to the 16 personality combinations.


## Conclusion:
Our paper concludes that it is indeed possible to use word embedding to classify the personality type of an individual based on their social media posts. With the use of Logistic Regression, it has been demonstrated that personality type of an individual can be inferred to some extent. For that reason, the alternative hypothesis stated in our paper can be rejected.  Additionally, increasing the vector size of a document embedding beyond 80 does not seem to significantly increase the performance of the model overall. Furthermore, the additional assumption can be formulated that Doc2Vec contributed heavily towards the performance of the classification models used. It is recommended to pursue further research in order to validate this assumption.
      
    

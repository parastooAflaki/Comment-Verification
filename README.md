# Comment-Verification
DigikalaNext contest - 2019

Implemented a comment verification system using CountVectorizer, Bayes algorithm and Digikala website's comments dataset

* Scikit-learn's Countvectorizer  : 
   
   Transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.
* Bayes theorem

    ![image](https://user-images.githubusercontent.com/47450201/152576959-ca205e44-8892-45a8-a5ca-17b194d9fc4a.png)

  ![image](https://user-images.githubusercontent.com/47450201/152577838-cf85bd5e-d69f-4ef0-bf14-b3bbea11cc81.png)
    
    The “prior” P(A) and the “evidence” P(B) are the probabilities of observing A and B independently in the document, whereas the “posterior” and the “likelihood” are the conditional probabilities of observing A given B and vice versa.
    
    In this project what we are going to find is this:
    ![image](https://user-images.githubusercontent.com/47450201/152577182-798ff591-436b-4064-ab27-012ca409c35c.png)

  While x is a feature vector containing the sequence of words in the given comment.

The “Naive” assumption that the Naive Bayes classifier makes is that the probability of observing a word is independent of others. Therefore, the probability of that comment being a spam is the product of seeing each of the words in the comment if a spam comment.

![image](https://user-images.githubusercontent.com/47450201/152577715-a634b805-4cfd-4d23-bf70-1d62e610b8c5.png)


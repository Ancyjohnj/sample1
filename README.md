         Text Emotion Classification using Machine Learning



Project Overview



This project focuses on classifying emotions in text comments using Machine Learning techniques.



#The dataset contains text comments labelled with three emotions:



Anger



Fear



Joy



Two Machine Learning algorithms, Multinomial Naive Bayes and Linear Support Vector Machine (SVM), were implemented and compared.



#3Dataset Information



Total records: 5,937



Features: Comment, Emotion



Target classes: Anger, Fear, Joy



Missing values: 0



Duplicate rows: 0



#Technologies Used



Python



Pandas



NumPy



Regular Expressions



NLTK



Scikit-learn



Matplotlib



Seaborn



Jupyter Notebook




#Data Preprocessing



The following preprocessing steps were performed:



Converted text into lowercase.



Removed special characters and numbers.



Tokenized the text into individual words.



Removed English stopwords.



Preserved negation words such as "not", "no", "nor", and "never".



Joined the filtered tokens to create the final cleaned text.



Feature Extraction



TF-IDF (Term Frequency–Inverse Document Frequency) Vectorizer was used to convert text data into numerical features.



Feature matrix shape: 5937 × 8818



TF-IDF gives importance to words based on their frequency in a document and across the dataset.



Machine Learning Models



Two classification algorithms were trained:



Multinomial Naive Bayes



Linear Support Vector Machine (SVM)



#The dataset was divided into:



Training data: 80%



Testing data: 20%



Stratified splitting was used to maintain the emotion distribution.



#Model Evaluation



The models were evaluated using accuracy, precision, recall, F1-score, classification reports, and confusion matrices.



Model



Accuracy



Multinomial Naive Bayes



89.06%



Linear SVM



93.77%



Result



Linear SVM achieved the highest accuracy of 93.77%, while Multinomial Naive Bayes achieved 89.06%.



Therefore, Linear SVM performed better than Naive Bayes on this dataset and was selected as the best-performing model.




#Conclusion



This project demonstrates how Machine Learning techniques can be used to classify emotions from text data.



Text preprocessing and TF-IDF feature extraction helped convert raw text into meaningful numerical features. Both Naive Bayes and SVM models were successfully trained and evaluated.



Based on the evaluation results, Linear SVM achieved better performance with 93.77% accuracy.



#Project Files



Text_Emotion_Classification.ipynb – Jupyter Notebook containing the complete implementation.



nlp_dataset.csv – Dataset used for training and testing.


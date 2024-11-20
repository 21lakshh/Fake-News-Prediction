# **Fake News Prediction**  
The Fake News Prediction ML Model is designed to classify news articles as either fake or real. It uses machine learning techniques, combining text preprocessing and feature extraction with a Logistic Regression classifier.   

## **Features**  
### **Text Preprocessing**  
**Stemming**: To reduce words to their root forms.  
eg --> running -- (run) jumps --> (jump) etc

**Vectorization**: TF-IDF (Term Frequency-Inverse Document Frequency), Gives high importance to unique words that maybe useful, learns the vocabulary and inverse document frequencies for each word in the data. words that appear frequently are given less importance and converts all textual data into feature vectors (numeric data)  

**Model Selection**: Logistic Regression to predict whether news is fake or real.  
- Accuracy on Training Data: 98.63%  
- Accuracy on Testing Data: 97.90%

This model can be used in real-world applications to combat misinformation, improve content moderation, and enhance trust in media.  

Link For Dataset --> https://drive.google.com/file/d/1wqcX7CvlX-kuPBaQXJMxCzZaMixiyISZ/view?usp=sharing

# Fake News Prediction Model

This repository contains a machine learning model designed to classify news articles as either **fake news** or **real news**. The model utilizes logistic regression to achieve high accuracy and implements various preprocessing steps to convert textual data into meaningful numerical representations.

## Features

- Handles missing values in the dataset by replacing them with empty strings (`""`).
- Implements a stemming procedure to reduce words to their root forms (e.g., "running" → "run").
- Uses **TF-IDF Vectorizer** to convert textual data into numerical form.
  - Assigns high importance to unique and meaningful words.
  - Gives lower importance to frequently appearing words.
  - Excludes common stop words to improve the quality of features.
- Visualizes the dataset distribution using a pie chart for better insights.
- Trained on a **Logistic Regression** model to classify fake vs. real news.

## Dataset Overview

The dataset contains labeled text data of news articles with the following preprocessing steps applied:

1. **Handling Null Values**: Replaced null values in the dataset with empty strings (`""`).
2. **Stemming**: Applied stemming to reduce words to their root forms, improving model generalization.
3. **TF-IDF Vectorization**:
   - Transform textual data into numeric form.
   - Focus on unique, meaningful words while reducing the impact of commonly appearing words.

### Dataset Visualization

The distribution of fake and real news in the dataset is visualized using a pie chart:

- Pie chart depicts the proportion of fake vs. real news articles in the dataset.

## Model Training

- **Algorithm**: Logistic Regression
- **Training Accuracy**: 98.63%
- **Testing Accuracy**: 97.90%

The model's performance demonstrates its ability to effectively classify fake vs. real news with high accuracy.

## Key Libraries Used

- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and handling.
- **Scikit-learn**: For machine learning algorithms and TF-IDF Vectorizer.
- **Matplotlib**: For dataset visualization.
- **NLTK**: For stemming and natural language preprocessing.

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the model or documentation.

Link For Dataset --> https://drive.google.com/file/d/1wqcX7CvlX-kuPBaQXJMxCzZaMixiyISZ/view?usp=sharing

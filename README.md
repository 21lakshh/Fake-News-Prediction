# Fake News Prediction Model
This repository contains a machine learning model designed to classify news articles as either **fake news** or **real news**. The model implements various preprocessing steps to convert textual data into meaningful numerical representations and compares multiple classification algorithms to achieve optimal performance.
## Features
- Handles missing values in the dataset by replacing them with empty strings (`""`).
- Implements a stemming procedure to reduce words to their root forms (e.g., "running" → "run").
- Uses **TF-IDF Vectorizer** to convert textual data into numerical form.
  - Assigns high importance to unique and meaningful words.
  - Gives lower importance to frequently appearing words.
  - Excludes common stop words to improve the quality of features.
- Visualizes the dataset distribution using a pie chart for better insights.
- Trained and compared multiple machine learning models: **Logistic Regression**, **Decision Tree Classifier**, and **Random Forest Classifier**.
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
Three different machine learning algorithms were trained and evaluated on the preprocessed dataset to determine the best-performing model for fake news classification:

### Logistic Regression
- **Accuracy**: 97.91%
- **Precision**: 97.95%
- **Recall**: 97.91%
- **F1-score**: 97.91%
- **Score**: 97.91%

### Decision Tree Classifier
- **Accuracy**: 99.18%
- **Precision**: 99.18%
- **Recall**: 99.18%
- **F1-score**: 99.18%
- **Score**: 99.18%

### Random Forest Classifier (Best Model)
- **Accuracy**: 99.33%
- **Precision**: 99.33%
- **Recall**: 99.33%
- **F1-score**: 99.33%
- **Score**: 99.33%

### Results Comparison
The following table summarizes the performance metrics for all three models:

| Model | Accuracy | Precision | Recall | F1-score | Score |
|-------|----------|-----------|--------|----------|-------|
| Logistic Regression | 97.91% | 97.95% | 97.91% | 97.91% | 97.91% |
| Decision Tree Classifier | 99.18% | 99.18% | 99.18% | 99.18% | 99.18% |
| Random Forest Classifier | **99.33%** | **99.33%** | **99.33%** | **99.33%** | **99.33%** |

The **Random Forest Classifier** achieved the best performance across all metrics, demonstrating superior ability to classify fake vs. real news with an accuracy of 99.33%.
## Key Libraries Used
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and handling.
- **Scikit-learn**: For machine learning algorithms and TF-IDF Vectorizer.
- **Matplotlib**: For dataset visualization.
- **NLTK**: For stemming and natural language preprocessing.
## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request to improve the model or documentation.
Link For Dataset --> https://drive.google.com/file/d/1wqcX7CvlX-kuPBaQXJMxCzZaMixiyISZ/view?usp=sharing

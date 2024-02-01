# NLP-Sentiment-Analysis-on-Healthcare-Reviews
Name : SRINIVASAN M
Batch : DW77DW78
Linkedin : https://www.linkedin.com/in/srinivasan-m-754033bb/
### **DOMAIN** : **Healthcare**
### **AIM** : **Analyzing and Classifying the Sentiments (Positive, Negative and Neutral) based on the Healthcare Reviews dataset..**

### **Introduction**
This project focuses on Natural Language Processing (NLP) and sentiment analysis applied to healthcare reviews. The goal is to analyze sentiments expressed in reviews to gain insights into the opinions and experiences of healthcare consumers. The project utilizes machine learning models to categorize reviews into positive, negative, and neutral sentiments.

### **Problem Statement**
The problem at hand is to analyze sentiments in healthcare reviews. By understanding the sentiments expressed in patient reviews, healthcare providers can identify areas for improvement, enhance patient satisfaction, and ultimately improve the quality of care.

### **Tasks**
### 1. **Data Preprocessing**
The data preprocessing step involves cleaning and preparing the raw healthcare reviews dataset for analysis. Key tasks include:

- Convert Review_Text to Lowercase
- Text Cleaning: Remove unnecessary characters, symbols, and irrelevant information.
- Tokenization: Break down sentences into individual words (tokens).
- Stopword Removal: Eliminate common stopwords that do not contribute significantly to sentiment analysis.
- Lemmatization: Reduce words to their base or root form.
- Stemming: Reducing words to their base or root form by removing suffixes, thereby simplifying variations of words to a common linguistic stem.
- POS Tagging : Assigning grammatical categories (such as nouns, verbs, adjectives) to words in a text to understand their syntactic roles within sentence
- Polarity : Assigning polarity to categorize sentiment of a text, indicating whether the expressed sentiment is positive, negative, or neutral.
- Text vectorization : TF-IDF vectorizer in NLP is a method that transforms a collection of documents into numerical vectors, emphasizing the importance of terms based on their frequency (TF) in a document and their rarity (IDF) across the entire corpus.
- Imbalance data handling : SMOTE (Synthetic Minority Over-sampling Technique) in machine learning is a method that generates synthetic samples for the minority class to address class imbalance, enhancing the performance of classification models.

### 2. **Sentiment Analysis Model**
  The sentiment analysis model is the core of this project. It involves training machine learning models to classify reviews into positive, negative, or neutral sentiments.    The following classification models are explored:

**Logistic Regression**
  Logistic regression is a linear model commonly used for binary classification tasks. In the context of sentiment analysis, it models the probability that a review belongs to a particular sentiment class.
**K-Nearest Neighbors (K-NN)**
  K-NN is a non-parametric, instance-based learning algorithm. It classifies a new data point based on the majority class of its k-nearest neighbors in the feature space.
**Support Vector Machines (SVM)**
  SVM is a powerful classification algorithm that finds the hyperplane that best separates data into different classes. It can handle both linear and non-linear classification.

### 3. **Model Evaluation**
  Model evaluation is crucial for assessing the performance of sentiment analysis models. Key metrics include accuracy, precision, recall, and F1-score. Cross-validation and hyperparameter tuning are employed to optimize model performance.

**Training Data**
1. The models have achieved perfect accuracy on the training set, as evidenced by the training accuracy of 1.00.
2. The classification report and confusion matrix suggest that the model is making correct predictions for each class, with precision, recall, and F1-score all equal to 1.00

**Testing Data**
1. The model achieved perfect accuracy on the test set, which aligns with the results on the training set.
2. The classification report and confusion matrix suggest that the model is making correct predictions for each class, with precision, recall, and F1-score all equal to 1.00.

**Cross-Validation of Models**
1. All individual cross-validation accuracy scores on the training and testing data are 1.0 (100%). This suggests that, in each fold, the model achieved perfect accuracy on the training and testing data.
2. The mean accuracy on the training  and testing data is also 1.0, indicating that the model consistently performed well across different subsets of the training and testing data during cross-validation

In summary, High accuracy on the testing set is indicative of a well-performing model. The model appears to generalize well to different subsets of both the training and testing data, as indicated by the consistent perfect accuracy scores in cross-validation as well. It is essential to approach model evaluation with a critical eye and consider the broader context of the dataset and problem

### **4. Insights and Visualization**
In this phase, the project aims to derive actionable insights from the sentiment analysis results. Visualizations, such as word clouds and sentiment distribution plots, help in presenting findings in an interpretable manner.

**Count of sentiments:**
Sentiment          Count
Positive reviews    515
Negative            387
Neutral              98

**Top 10 Recurring Words:** 
  - experience
  - service
  - provider
  - healthcare
  - bad
  - im
  - satisfied
  - received
  - highly
  - recommended

**Most frequently used words:**
**Positive Reviews:** 
  - service	208
  - highly	117
  - satisfied	117
  - recommended	117
  - received	117 
- Customers are highly satisfied and recommend the service.
 
**Negative Reviews :** 
  - experience	281
  - provider	187
  - bad	184
  - service	106
  - disappointing	106
- Customers had a bad, disappointing experience and service.

**Neutral Reviews:**
  - experience	281
  - provider	187
  - bad	184
  - service	106
  - disappointing	106
- Customers had a bad, disappointing experience and service.

### **Recommendations**

**1. Address Negative Reviews:**
- Common Issues: Analyzing negative reviews identified common issues or concerns raised by patients are bad service is provided and they are disappointed.
- Root Cause Analysis: Conduct a root cause analysis to understand the underlying problems leading to negative feedback.
- Implement Solutions: Develop and implement action plans to address the identified issues.

**2. Promote Positive Reviews:**
- Encourage Feedback: Actively encourage patients to leave reviews, especially those who have had positive experiences.
- Highlight Success Stories: Share positive patient stories and testimonials on the hospital's website or social media to build trust.

**3. Improve Communication:**
- Patient Communication: Enhance communication between medical staff and patients. Ensure that information about procedures, treatments, and recovery plans is conveyed clearly.
- Feedback Mechanism: Establish a feedback mechanism for patients to share concerns and suggestions during their stay.

**4. Staff Training:**
- Customer Service Training: Provide ongoing training for hospital staff in customer service and patient communication.
- Empathy and Compassion: Emphasize the importance of empathy and compassion in patient interactions.

**5. Quality of Care:**
- Clinical Excellence: Prioritize and continually improve the quality of medical care and services provided.
- Patient Outcome Monitoring: Regularly monitor patient outcomes and take measures to enhance medical performance.

**6. Patient-Centered Approach:**
- Patient Satisfaction Surveys: Conduct regular patient satisfaction surveys to gather feedback on various aspects of their experience.
- Patient-Centered Policies: Implement policies that prioritize the comfort and well-being of patients.

**7. Online Presence**
- Responsive Online Presence: Maintain an active and responsive online presence. Address reviews and concerns promptly.
- Educational Content: Share educational content and resources on the hospital's website to keep patients informed.

**8. Employee Well-being:**
- Staff Support Programs: Implement programs to support the well-being and mental health of hospital staff.
- Recognition and Incentives: Recognize and reward staff for excellent patient care and positive contributions.

**9. Continuous Improvement:**
- Performance Metrics: Establish key performance indicators (KPIs) to measure hospital performance and continuously improve based on data.
- Regular Audits: Conduct regular internal audits to assess adherence to quality standards and patient satisfaction.

Feel free to explore the codebase and adapt it for similar projects or different datasets. For any questions or issues, please contact srinicheenu5658@gmail.com.

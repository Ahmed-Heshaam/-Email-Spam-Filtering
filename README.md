# -Email-Spam-Filtering
This project aimed to develop a machine learning model for email spam filtering using a dataset of emails. The implemented model, based on a Naive Bayes classifier, demonstrated an impressive accuracy of 97%. This report provides an overview of the project, the dataset used, the methodology applied, and the achieved results.

Objectives
The primary objectives of this project were:

Build a Spam Filtering Model: Develop a machine learning model capable of accurately classifying emails as spam or ham (non-spam).

Achieve High Accuracy: Attain a high level of accuracy in spam classification to enhance the effectiveness of the email filtering system.

Dataset
The dataset used in this project consists of emails labeled as either spam or ham. The dataset's key features include:

text: The body of the email.
label: A binary label indicating whether the email is spam (1) or ham (0).
Methodology
1. Data Preprocessing
Label Encoding: Converted the categorical 'label' column into numerical values (1 for spam, 0 for ham).
Text Tokenization: Tokenized the email text using the NLTK library, converting it into a format suitable for machine learning.
2. Train-Test Split
Split the dataset into training and testing sets to evaluate the model's performance on unseen data.
3. Feature Extraction
Used the CountVectorizer from scikit-learn to convert the email text into numerical features for model training.
4. Model Training
Implemented a Naive Bayes classifier (MultinomialNB) for training the spam filtering model.
5. Model Evaluation
Evaluated the model on the test set to measure its accuracy and generated a classification report.
Results
The implemented model achieved an impressive accuracy of 97% on the test set. The classification report provides detailed metrics on precision, recall, and F1-score for both spam and ham classes.

Future Work
While the current model demonstrates strong performance, there are opportunities for further improvement and exploration:

Feature Engineering: Experiment with different feature extraction methods to capture more nuanced information from the email text.

Hyperparameter Tuning: Fine-tune model hyperparameters to potentially boost performance.

Ensemble Methods: Explore the use of ensemble methods or other advanced machine learning models for comparison.

Conclusion
In conclusion, the developed email spam filtering model showcases robust performance with a 97% accuracy rate. The project successfully achieved its objectives and provides a foundation for further enhancements. The insights gained from this project can contribute to the development of more effective and accurate email filtering systems.

Acknowledgments
The successful completion of this project was made possible by leveraging the NLTK and scikit-learn libraries. Special thanks to the contributors and maintainers of these open-source libraries.

# Spam Email Detection using Logistic Regression

This project focuses on building a spam email detection model using logistic regression. It was completed as part of a data science internship provided by Oasis Infobyte.

## Project Overview

The goal of this project is to develop a machine learning model that can accurately classify emails as spam or non-spam (ham). Logistic regression is used as the classification algorithm due to its effectiveness in binary classification tasks.

## Dataset

The project utilizes a dataset containing a collection of emails labeled as spam or ham. The dataset is preprocessed and contains the following columns: 'v1' (label) and 'v2' (email content).

## Implementation

The project involves the following steps:

1. Data preprocessing: The dataset is loaded and preprocessed, including removing unnecessary columns and cleaning the text data.

2. Feature extraction: The text data is transformed into numerical feature vectors using the TF-IDF (Term Frequency-Inverse Document Frequency) technique.

3. Model training: Logistic regression is trained on the preprocessed data, using the feature vectors and corresponding labels.

4. Model evaluation: The trained model is evaluated using appropriate performance metrics such as accuracy, precision, recall, and F1-score.

5. Prediction: The model is used to predict the class labels of new email data, enabling spam email detection.



## Dependencies

The project requires the following Python libraries:

- pandas
- scikit-learn
- numpy

These dependencies can be installed using `pip` or `conda` package managers.

## Usage

To use the project code, follow these steps:

1. Clone the repository from the GitHub repository link.

2. Install the required dependencies using `pip` or `conda`.

3. Run the Python scripts in the `code/` directory in the specified order, following the instructions provided within the scripts.

4. Evaluate the model performance using the evaluation metrics obtained.

5. Use the trained model for predicting the class labels of new email data.

## Conclusion

The spam email detection model developed using logistic regression provides an effective solution for identifying and classifying spam emails. It can be further improved by exploring different feature engineering techniques, experimenting with different algorithms, and fine-tuning the model hyperparameters.

For more details, refer to the project code and documentation available in the GitHub repository.

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT).

For any further questions or inquiries, please contact me at [email address].

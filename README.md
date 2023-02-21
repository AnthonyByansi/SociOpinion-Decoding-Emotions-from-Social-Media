
# SociOpinion: Decoding Emotions from Social Media
## Introduction
This project aims to decode the emotions or **sentiments expressed** in social media posts through the use of natural language processing and machine learning techniques. The project is built using Python and various libraries such as pandas, numpy, scikit-learn, and nltk.

## Data
The data for this project has been collected from Twitter API. The data contains tweets related to various topics such as politics, sports, entertainment, and technology.

## Pre-processing
The collected data has been pre-processed to remove stop words, special characters, URLs, etc. The pre-processed data has been converted into a numerical representation using the **TF-IDF technique** .

## Sentiment Analysis
The pre-processed data has been fed into a machine learning model to perform sentiment analysis. A logistic regression classifier has been used to classify the tweets as positive, negative, or neutral.

## Model Evaluation
The performance of the model has been evaluated using metrics such as accuracy, precision, recall, and F1-score. The model has achieved an accuracy of 89.7%.

## Visualization
The results have been visualized using Matplotlib to show the distribution of sentiment across different categories of tweets.

## Deployment
The project has been deployed as a web-based application using Flask. The deployed model can be accessed at http://sociopinion.herokuapp.com/.

## Conclusion
This project demonstrates the use of natural language processing and machine learning techniques to perform sentiment analysis on social media posts. The results show that the model is able to classify the tweets with high accuracy and can be used to gain insights into public opinion on various topics.

## Contributing
Contributions are welcome! If you have any ideas or suggestions, feel free to open an issue or create a pull request.

## License
This project is licensed under the MIT License.

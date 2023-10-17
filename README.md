# Forage-Virtual-Internship
## Task 1: WebScraping to Gather Data on Customer Reviews
I used the library BeautifulSoup to get data from the website that was provided.
Sentiment analysis ws performed on the data to know how customers feel about British Airway flight
![wordcloud](https://github.com/Adebesin-Aramide/Forage-Virtual-Internship/assets/91395326/f7d13dfa-ee7a-4d30-9d56-4cc651979527)
From the wordcloud image didplayed above, the key topics in customer review are flight, BA, seat...
![piechart](https://github.com/Adebesin-Aramide/Forage-Virtual-Internship/assets/91395326/7a508ec9-8981-44a8-bb54-7e8a44a67705)
64.4% of the customers gave positive reviews, 34.2% gave negative review while 1.4% were neutral

## Task 2: Building a Predictive Model to determine whether a customer complete booking
For this task the dataset was provided and it was a clean datatet
- Data Preprocessing was done by handling the imbalance target variable, encoding categorical columns
- Feature Selection was done by using the chi-square method
- Multicollinearity was avoided by using the variance inflation factor
- Multiple model was iterated and the best performing model which was eventually used after cross-validation is the RandomForestClassifier with an accuracy of 93%.
  ![features_imp](https://github.com/Adebesin-Aramide/Forage-Virtual-Internship/assets/91395326/4a2714d8-ce2b-4d42-8252-f1e1cb235a88)
  Displayed above are the feature importance that contributed greatly to the prediction.

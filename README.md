# Customer Feedback and Booking Prediction for British Airways

**This repository showcases a comprehensive exploration of data science methodologies applied to enhance customer acquisition strategies and insights at British Airways by analysing customer feedback and booking data.**

**Data Collection:** Customer feedback data was collected using beautifulSoup to Scrape Customer reviews from a website with paginated data. Also, a high-quality data of booking activity was provided as a CSV file.

**Data Preprocessing:** The Customer feedback data was preprocessed using NLTK to clean, remove stopwords, and lemmatize the text. The booking data was cleaned by encoding the categorical variable and mapping values.

**Data Analysis:** The customer feedback data was analyzed using LDA to discover the main topics in the customer reviews. The sentiment of each review was also classified as positive, neutral, or negative using TextBlob. The booking data was analyzed using a RandomForestClassifier to predict booking completion and to identify the factors that affect booking success.

**Data Visualisation:** The results of the data analysis were visualized using matplotlib and seaborn. A scatter plot, a histogram, and a word cloud were created to display the results of topic modeling and sentiment analysis. A bar plot was created to show the feature importances of the RandomForestClassifier.

**Report Development:** A report to communicate the results across platforms was developed and shared. The report included a summary of the project objectives, methods, and outcomes, as well as relevant visualizations and references.

_This project was inspired by the British Airways Data Science Virtual Programme._

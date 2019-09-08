# Presidential_Quote_Text_Analysis
A brief NLP project using various past president's quotes for classifying text.<br>
Let's see if we can train a model to be able to predict which president said what.<br>

<h2>Data</h2>
The data for this project came from goodreads.com. A total of about 2000 quotes were scraped using BeautifulSoup4 along with the president who said the quote. After cleaning the data, I will use machine learning models to attempt to classify quotes to their speakers. 

<h2>Text Preprocessing</h2>
<ul>Tokenize</ul>
<ul>Remove Stop Words</ul>
<ul>Lemmatize</ul>
<ul>Label Encode</ul>

<h2>Initial Political Party Classisification Test Accuracies</h2>
<ul>Naive Bayes: 79.0%</ul>
<ul>Logistic Regression: 86.4%</ul>
<ul>XGBoost: 79.6%</ul>

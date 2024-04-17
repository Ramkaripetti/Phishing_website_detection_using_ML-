# Phishing_website_detection_using_ML-
## Introduction

The Internet has become an indispensable part of our life, However, It also has provided opportunities to anonymously perform malicious activities like Phishing. Phishers try to deceive their victims by social engineering or creating mockup websites to steal information such as account ID, username, password from individuals and organizations. Although many methods have been proposed to detect phishing websites, Phishers have evolved their methods to escape from these detection methods. One of the most successful methods for detecting these malicious activities is Machine Learning. This is because most Phishing attacks have some common characteristics which can be identified by machine learning methods. To see project click [here]("/").


## Installation
The Code is written in Python 3.8.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Directory Tree 
```
├── pickle
│   ├── model.pkl
├── static
│   ├── styles.css
├── templates
│   ├── index.html
├── Phishing URL Detection.ipynb
├── Procfile
├── README.md
├── app.py
├── feature.py
├── phishing.csv
├── requirements.txt


```
## Result

Accuracy of various model used for URL detection
<br>

<br>

||ML Model|	Accuracy|  	f1_score|	Recall|	Precision|
|---|---|---|---|---|---|
0|	Gradient Boosting Classifier|	0.974|	0.977|	0.994|	0.986|
1|	Random Forest|	                0.967|	0.971|	0.992|	0.991|
2|	XGBoost Classifier| 	        0.970|	0.973|	0.993|	0.984|
3|	Decision Tree|      	        0.958|	0.962|	0.991|	0.993|
4|	Naive Bayes Classifier|     	0.605|	0.454|	0.292|	0.997|

Feature importance for Phishing URL Detection 
<br><br>
![image](https://github.com/Ramkaripetti/Phishing_website_detection_using_ML-/assets/166406095/4f4f80a3-6437-47f4-b178-3bba8ad844bd)





## Conclusion
1. This survey presented various algorithms and approaches to detect phishing websites by several researchers in Machine Learning. On reviewing the papers, we came to a conclusion that most of the work is done by using familiar machine learning algorithms like Naïve Bayesian, GBC, Xgboost,Decision Tree and Random Forest.
2. The final take away from this project is to explore various machine learning models, perform Exploratory Data Analysis on phishing dataset and understanding their features. 
3. Gradient Boosting Classifier correctly classifies URL up to 97.4% respective classes and hence reduces the chance of malicious attachments.
4. ![Screenshot (92)](https://github.com/Ramkaripetti/Phishing_website_detection_using_ML-/assets/166406095/cca175cb-a3c4-4592-b9dd-f24c2c9b9e35)
5. ![Screenshot (93)](https://github.com/Ramkaripetti/Phishing_website_detection_using_ML-/assets/166406095/1b0268f5-2d21-44e7-b65d-109ca3ad9060)





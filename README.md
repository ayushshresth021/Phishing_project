# Phishing_project

Our approach to combat the problem of phishing by detecting these emails using trained Machine Learning models to determine whether it believes it’s a phishing email or not.

**Architecture, Design, and Key Algorithm**

**Phishing Email Detection Models**<br>
<ul>
 <li> Algorithms: Logistic Regression, Random Forests Classifier, Naive Bayes Classifier (Gaussian)</li>
 <li> Datasets: Kaggle and https://monkey.org/~jose/phishing/</li>
 <li> Feed vectorized text into the machine learning models</li>
<li> Email text extractor</li>
</ul>  
  
**Phishing URL Detection Models**<br>
<ul>
 <li> Algorithms: Logistic Regression, Random Forests Classifier, Naive Bayes Classifier (Gaussian), Feedforward Neural Network</li>
 <li> Dataset: Kaggle</li>
 <li> Feed a vector of 10 features into the machine learning models</li>
</ul>
Tools: <br>
Python, Scikit-learn, Pandas, and Numpy libraries<br>

# Installation 
Tools required are:
- Python
- Scikit-learn version 1.2.2 (Required to be this specific version)
- Pandas
- Numpy libraries



**Live Demo**

https://github.com/ayushshresth021/Phishing_project/assets/127001000/83c00a90-f6e0-45d1-8a29-a5d5a176f129

The program has the prerequisite need to have an .eml file, which can be taken from any email provider you can find and use.

For this example, we have two test .eml files, the first one “safe email.eml”  which has no signs of phishing, while the other file “sign_up.eml” has a recent scam url link which makes it a phishing email.

The phishing detection application basically has you select the browse button to find the .eml file in the directory and once you have the file, you begin the phish check which will go through the information found in the email, specifically the plain text and url content found in the email body, to determine if it is a legitimate or phishing email.

As you can see through the results of the program for safe email, the safe email.eml file is found to be unlikely a phishing email. While browsing through the directory for the sign_up email, the phish check returns that the url is 100% a phishing link, which the program accurately determines that the email is a phishing attack.

**Phishing URL detector Accuracy using Random Forest Algorithm**
![Screenshot 2023-12-09 at 1 38 59 PM](https://github.com/ayushshresth021/Phishing_project/assets/127001000/344cc5fb-11cc-4bde-8a2c-93e93a1e8ad8)

**Phishing Email detector Accuracy using Logistic Regression Algorithm**
![Screenshot 2023-12-09 at 1 39 09 PM](https://github.com/ayushshresth021/Phishing_project/assets/127001000/82a51396-cc66-4f69-9390-0bc7f2a7bfe0)







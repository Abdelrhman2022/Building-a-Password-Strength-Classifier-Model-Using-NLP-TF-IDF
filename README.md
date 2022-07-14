# Building a Password Strength Classifier Model Using NLP TF IDF 
Password Strength Classifier Using NLP and Logistic Regression. The task is to check Password strength using Logistic Regression ML Model. For Processing the text data I've used TF-IDF which is a NLP technique to Preprocess the text data into vectors for ML models. It shows three values(0 , 1 , 2) i.e. 0 for weak, 1 for medium, 2 for strong. Strength of the password based on rules(such as containing digits, special symbols , etc.)

# Problem Defination 
Password strength is used to measure how effective a password is against external attacks. External attacks are in form of password cracking or brute-force attacks. They aim to gain unauthorized access to a computer system or network. The strength of a password is usually measured using its complexity, length, and unpredictability.
Cyber crimes and data breaches are on the rise, and the main cause for this is usually compromised passwords.


# Dataset

Password - 670k unique values for password collected online. Strength - three values(0 , 1 , 2) i.e. 0 for weak, 1 for medium, 2 for strong. Strength of the password based on rules(such as containing digits, special symbols , etc.) 

The passwords used in our analysis are from 000webhost leak that is available online. How did we figure out which passwords were stronger and which were weaker? Well, there is a tool called PARS by Georgia Tech university which have all the commercial password meters integrated into it. All I did was give that tool all the passwords and it gave me new files for each commercial password strength meter. The files contained the passwords with one more column i.e their strength based on the commercial password strength meters.
The commercial password strength algorithms I used are of Twitter, Microsoft and battle. How is this algorithm different from these strength meters? First of all, it is entirely based on machine learning rather than on rules. Secondly, I only kept those passwords that were flagged weak, medium and strong by all three strength meters. This means that all the passwords were indeed either weak, medium or strong.

[Dataset Link](https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset)




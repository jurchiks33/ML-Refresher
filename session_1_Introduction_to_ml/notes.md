
Machine Learning is basically teaching computers to learn patterns from data so they can make predictions or decisions without you hard coding every rule.

Traditional programming: you write rules => computer follows rules => output.

Machine Learning: You give examples(data)=>correct answers(sometimes)=>algorithm learns rules automatically=>model produces output.

ML is a method where computer builds a model from data.
 * Data/Dataset: the examples you train on(rows of information)
 * Features(X): the input variable(columns) you use (age, proce, clicks, volume, etc.)
 * Label/Target(y): the answer you want to predict(spam/not spam, house price, yes/no)
 * Model: the learned function that maps input => output
 * Training: The learning phase where the model adjusts itself to reduce mistakes.
 * Inference (prediction): using the trained model on new unseen data.
 * Generalization: How well the model performs on new data (the real goal)

 2) Types of Machine Learning.

 * Supervised Learning (Most common in business)
 You have inputs + correct answers(labels)
 Two main tasks:
 - Classification
    * spam vs not spam
    * fraud vs not fraud
    * customer yes/no
    * disease positive/negative

- Regression (predict number)
    * house price
    * sales forecast
    * temperature tomorrow
    * stock return prediction
Supervised learning is often used when you have historical outcomes.

* Unsupervised Learning
You have inputs but no labels. The goal is discover structure.
Common tasks:
- Clustering
    Group similar things together
    * customer segmentation
    * grouping similar products
    * finding behavior groups in app usage.
- Dimensionality reduction
    Compares features while keeping important structure.
    * Visualization (turn 100 features into 2D plot)
    * noise reduction
    * speed up models
- Anomaly detection
    Find wierd or rare cases
    * unusual network activity(cybersecurity)
    * fraud patterns
    * faulty sesors in IoT
 
* Semi supervised Learning.
    You have a small labeled dataset and big unlabeled dataset. 
    - 2000 labeled images and 200 000 unlabeled images

* Self supervised Learning(huge in modern AI)
    The model creates its own learning tasks from raw data.
    - example would be a hide word and predict it.


* Reinforcment Learning (LR)
    Learning by trial and error
    - robotic
    - game AI
    - dynamic pricing
    -some trading research
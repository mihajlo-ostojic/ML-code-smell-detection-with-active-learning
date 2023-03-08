# Code Smell Detection using Machine Learning and Active Learning
This project uses machine learning models to detect code smells in software projects, with an active learning technique to improve model performance.


Code smells are signs of poor code design or implementation that can lead to problems such as maintenance difficulties and decreased software quality. Detecting code smells is crucial for improving software quality and maintainability.


The project uses a variety of machine learning models, such as Random Forest, XGBOOST, SVM, and Neural Networks, to classify code smells in software projects. Additionally, active learning is used to select the most informative instances for labeling, in order to improve the performance of the classifier with the smallest possible number of labeled instances.


Project is done using Tensorflow, keras.


Code is contained and explained in .ipynb files.


I used anaconda to create environment and install packages for project. All required packages are listed in requirements.txt file.


File god class show code for traning models to recognize god class code smell, while god class -active learning shows how to implement active learning loop and train models.
File long methode show code for traning models to recognize long methode code smell, while long methode -active learning shows how to implement active learning loop and train models.

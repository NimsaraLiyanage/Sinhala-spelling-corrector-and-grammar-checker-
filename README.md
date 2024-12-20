# Sinhala spelling corrector and grammar checker
(Semester 7 AI module project)

## **Sinhala spelling corrector**

Two methods were used to implement the Sinhala spelling corrector. LSTM model model performs well with 95.46% accuracy.

![5](https://github.com/user-attachments/assets/dfea5cc3-a8b5-424c-a02a-ce5588551421)

Here we used more than 100000 words labeled dataset to do this. Now You can See how sample inputs perform in LSTM model.

Inputs with wrong Spellings 

![Full Inputs](https://github.com/user-attachments/assets/aa03b111-5645-494f-85d3-bb5313d9b7f6)

Outputs with Correct Spellings

![Full Outputs](https://github.com/user-attachments/assets/c29de7d9-6640-4d91-8b77-70e7de5e2589)

Then We tried to make a simple GUI using the GRADIO python package. You have to install the Gradio package before using this.

Code 
![9](https://github.com/user-attachments/assets/890717ea-86e6-43d9-b173-8c6563cfb738)

GUI 
sample inputs and Outputs 

![1 GUI](https://github.com/user-attachments/assets/895ecbf5-5a60-4902-8966-bf7f995c0513)
![3 GUI](https://github.com/user-attachments/assets/e2d9f216-c8cc-4df6-9978-8576e3cee049)

_______________________________________________________________________________________________________________________________________

## **Sinhala Grammar Checker** 
We Used 3 approaches to make a Sinhala grammar checker.
1. Rule-Based Approach
2. ML - Random Forest Classifier 
3. DL - RNN

1. Rule-Based Approach

How It Works:

•	A set of predefined rules is created to identify and correct grammar errors.

sample inputs and Outputs 
![iNPUTS AND oUTPUTS](https://github.com/user-attachments/assets/2120eec6-e4c5-4426-8e12-2e66adf104fd)


2. Machine Learning (Random Forest Classifier)

How It Works:

•	A supervised machine learning model is trained on labeled examples of correct and incorrect Sinhala grammar to classify sentences or phrases as correct or incorrect.

sample inputs and Outputs 
![Final Inputs and Outputs](https://github.com/user-attachments/assets/65712a7e-d5f2-4f57-91a0-9654712e7a1c)


3. Deep Learning (Recurrent Neural Network - RNN)

How It Works:

•	Uses RNNs, a neural network designed to handle sequences of words and identify and correct grammar errors in Sinhala sentences. The model learns patterns in grammar from a large dataset.

sample inputs and Outputs 
![Output1](https://github.com/user-attachments/assets/010d5f89-bfba-405c-8a54-da0e5711b268)
![Output2](https://github.com/user-attachments/assets/2b8f2d33-2df4-4553-ada4-b060be2ecd25)

## **Combine Model**

To implement this, we combined the Random Classifier and LSTM model. This model responds to spelling and grammar mistakes simultaneously!

![Screenshot 2024-12-21 031315](https://github.com/user-attachments/assets/b57cad44-6d78-496a-ab11-364745b22ed5)





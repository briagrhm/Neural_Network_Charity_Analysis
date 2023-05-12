# Neural_Network_Charity_Analysis

## Analysis Overview 
The purpose of this project was to use deep learning neural networks. Tensorflow along wigth pandas and python were used to clean, analyze and create the model. We began by preprocessing the data for the neural network, then compile and trained the model and lastly evaluated the model and optimized. 

## Results 

### Data Preprocessing 
The variable target for this model is the "IS SUCCESFUL" column this tells us whether the money was used effectively. 
The features of this model are APPLICATION_TYPE,'AFFILIATION','CLASSIFICATION','USE_CASE','ORGANIZATION','INCOME_AMT','SPECIAL_CONSIDERATIONS'. 
The variables that are neither targets or features are EIN and Name and were dropped from the dataset both are identification information. 

### Compiling, Training, and Evaluating the Model
The deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively.
The provided 6061 total params. Once the model was trained this provided a 71.5% accuracy. To try and reach an accuracy of 75%, I added three more hidden layers and increased the neurons on one of layers. I also changed activation functions. This only increased the accuracy to 72.5%. I was unable to achieve the target model performance. 

## Summary 
The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.We could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.

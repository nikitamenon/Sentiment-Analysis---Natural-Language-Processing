# NLP Fashion E-Commerce Review Analysis 
### Aim: 
The aim of the project is to train a model using convolution neural network (CNN) to analyse a corpus of women’s clothing reviews to decide whether a product can be recommended to a shopper or not by extrapolating the sentiment of the existing customer reviews. For this project, a dataset from Kaggle called Women’s Clothing E-Commerce Reviews (company name omitted to preserve anonymity), will be used to train and test the model. This model’s performance will also be compared against that of a pre-trained model to evaluate its success.   
### Installation 
- Tensorflow 
- Keras
- NLTK
- SpaCy
- Seaborn 
### Existing Systems/Software Used:
#### Pre-Trained Model
- SpaCy and NLTK Libraries for model
- Matplotlib and Seaborn Python Libraries for data visualization
#### New Model
- NumPy and Pandas Python Libraries for pre-processing and handling
- Keras with Google TensorFlow for model
- Matplotlib and Seaborn Python Libraries for data visualization
### Expected Input/Output:
#### Pre-Trained Model 
The input is the review text after lemmatization and the output is a score between 0-1 for the categories 'positive', 'neutral', and 'negative'
#### The New Model 
The input is the review text after tokenisation and the output is a value between 0 to 1 indicating whether some this is recommended or not
### Structure of Jupyter Notebook
#### Part 1: Importing Libraries & Utilities
#### Part 2: Data Analysis 
- Understanding data set
- Cleaning of data set
- Finding trends in data 
#### Part 3: The Pre-Trained Model
- Pre-processing data 
- Assigning polarity scores to sentiment
- Compunding polarity scores 
- Performing a confusion matrix 
- Calculating classification accuracy 
#### Part 4: The New Model
##### 4.1 - Pre-Processing Data
##### 4.2 - Defining the Model 
##### 4.3 - Training the Model
##### 4.4 - Testing the Model 
##### 4.5 - Evaluating the Model 
- Performing a confusion matrix 
- Calculating classification accuracy 
#### Part 5: Evaluation 
### Acknowledgment 
A sincere appreciation to Nick Brooks for his data set on Women’s Clothing E-Commerce Reviews. 

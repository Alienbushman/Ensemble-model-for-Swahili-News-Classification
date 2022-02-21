# Ensemble models for Swahili News Classification 
## Where to get the data
To get the data to run this model, download the files from [swahili-news-classification](https://zindi.africa/competitions/swahili-news-classification/data)  and place them in a 'Data' folder
 
 ## How the code works
 - The model executes the machine learning models with use of the run\_features function
 - The choice of models is outlined in the all\_models function
 - Ensemble model: The model makes use of the models in all\_models outputing their prediction probababilty and outputting them as input features (using cross validation so that there is a prediction probability for each element using the function save\_feature\_probabilities). A second model then combines the prediction probabilities into a new model
  ## Extra insights
The rest is a simple to run jupyter notebook, along with an overview of the aproach in the file "Overview of aproach.pdf"

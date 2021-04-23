*AI Model Share Initiative at Columbia University*

# Mini-Hackathon 1 : **Tabular Data** - *Predict* country level happiness 

Find the best model to predict a country's happiness ranking using various social variables (including those measuring perceptions of corruption, GDP, maintaining a healthy lifestyle, or social support, etc.).
By running both DL and ML models, I could compare which ones showed stronger performance for this given task.

**Data**: 2019 World Happiness Survey Rankings + ISO 3166 Country Codes

**Model** : Convolutional neural network models using Keras + Machine Learning models

**Code** : https://github.com/jinokwon/AI-Model-Share-Projects-at-Columbia-Univ/blob/master/Project1/ML_DL_Project_1_Predicting_Happiness.ipynb

----
# Mini-Hackathon 2 : **Image Data** - *Predict* brain tumor

Find the best model to predict brain tumor using MRI image data.
I preprocessed (one-hot-encoded) image data and conducted object detection with deep learning models.

**Data**: 253 diagnositic brain MRI images

**Model**: Recurrent Neural Network models with Keras (w/ different numbers of hidden layers, epochs, and 2D Max Pooling, etc.)

**Code** : https://github.com/jinokwon/AI-Model-Share-Projects-at-Columbia-Univ/blob/master/Project2/ML_DL_Project_2_Predicting_Brain_Tumor_pynb.ipynb

---
# Mini-Hackathon 3 : **Text Data** - *Classify* BBC news categories

Find the best model to predict the category of a given news article with based on a short text from that article.
I ran various RNN (i.e., LSTM) models to conduct text classification.

**Data**: 2225 BBC News articles

**Model**: model: Neural network models with Keras
* 1) A model with an embedding layer and dense layers (but w/ no layers meant for sequential data)
* 2) A model using an Embedding layer with Conv1d Layers
* 3) A model using an Embedding layer with one sequential layer (LSTM or GRU)
* 4) A model using an Embedding layer with stacked sequential layers (LSTM or GRU)
* 5) A model using an Embedding layer with bidirectional sequential layers

**Code**: https://github.com/jinokwon/AI-Model-Share-Projects-at-Columbia-Univ/blob/master/Project3/ML_DL_Project_3_Classifying_BBC_News_Categories.ipynb

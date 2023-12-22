# BRAIT-Machine-Learning

# This Contains what Machine Learning's Team Do 
The job of Machine Learning team is to learn and make machine learning model of Braille Translator. The following are the work stages of the Machine Learning team

## 1. Search Dataset 
We collect the data from Kaggle and Google Images
### Dataset Resource
- [Kaggle](https://www.kaggle.com/datasets/shanks0465/braille-character-dataset)
- [Google Images](https://images.google.com/)

## 2. Data Preparation
After collecting the dataset, we do preparation data by cleaning the image that not suitable for our model, such as deleting and crop the image that still can be use
### Link To Dataset
- [Braille Dataset](https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/tree/main/BrailleDataset)
  
<a href="Braille Dataset" target="blank"><img align="center" src="https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/Documentation/Dataset%20Braille.jpg" height="500" width="600" /></a>


## 3. Preprocessing Data
We use image augmentation to the original images to create additional training samples to expanding the training data with diverse variations and to reduce overfiting. Preprocess the data using Label Encoding imported from sklearn.preprocessing.
### Link To Preprocessing File
- [Preprocessing](https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/BRAIT-MODEL/Preprocessing.ipynb)

* **Distribution of The Dataset**
  
<a href="Dataset Distribution" target="blank"><img align="center" src="https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/Documentation/Dataset.jpg" height="400" width="700" /></a>

* **Dataset Split**
  
We split the data into three folders. Namely train, validation and test. 

<a href="Dataset Split" target="blank"><img align="center" src="https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/Documentation/26%20Braille%20Classes.png" height="100" width="600" /></a>


## 4. Create Models and Training the Data
We created Convolutional Neural Network models using PyTorch Framework for Braille Classification

### Link BRAIT Model File
- [BRAIT Model](https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/BRAIT-MODEL/BRAIT_pytorch.ipynb)
  
* **Model Summary**
  
<a href="Model Summary" target="blank"><img align="center" src="https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/Documentation/Model%20Summary.png" height="400" width="700" /></a>

* **Train The Model**
  
<a href="BRAIT Model Loss And Accuracy" target="blank"><img align="center" src="https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/Documentation/Loss%20and%20Accuracy.png" height="500" width="300" /></a>


## 5. Evaluate The Model
After training the model, we carry out a model evaluation to ensure that the model that has been worked on can perform Braille translation tasks with a high level of accuracy.
* **BRAIT Model Loss and Accuracy**
  
<a href="Graphic Loss and Accuracy" target="blank"><img align="center" src="https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/Documentation/Graphic%20of%20Loss%20and%20Accuracy.png" height="300" width="600" /></a>

## 6. Test The Model
Testing models in the BRAIT project have an important role in ensuring that the model can work effectively and reliably in Braille translation tasks.

### Link To Testing File
- [Testing](https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/BRAIT-MODEL/control.ipynb)
  
* **BRAIT Model Testing**
  
<a href="BRAIT Model Testing" target="blank"><img align="center" src="https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/Documentation/PPT%20BRAIT%20(1).png" height="400" width="600" /></a>

## 6. Save The Model
* **Save Model**
  
<a href="Save Model" target="blank"><img align="center" src="https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/Documentation/Save%20Model.png" height="100" width="500" /></a>

This is our saved model file - [BRAIT_PYTORCH.pth](https://github.com/BRAIT-Braille-Translator/BRAIT-Machine-Learning/blob/main/BRAIT-WEIGHT/BRAIT_PYTORCH.pth)




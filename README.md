# Machine learning with Spark



## Project Intro
This work is about leveraging the power of spark to run some machine learning algorithms.
Spark is a power in-memory large-scale computing engine. We can interact with spark using different languages (**scala**,**Java**,**R**,**Python**).The latter will be used for this  project. Moreover, we will use the SparkML library that is very similar to scikit-learn to train our models.

### Technologies / Frameworks used 
* ![Static Badge](https://img.shields.io/badge/Python-3.8-green)
* ![Static Badge](https://img.shields.io/badge/Pyspark-3.5-green)


## Project Description
We will use the Titanic dataset. Our objective is to create a model that will predict the survability of the passengers.
In order to do so, we will use the following approach:
1. Exploritory data analysis
2. Data preparation </br>
*This step include the following filtering, missing values, imputation ...,feature extraction and feature engineering*
3. Model Training and evaluation </br>
*We will compare many models namely Gradient Boosting Decision Tree, Random Forest and Logistic Regression.
We will also do a Grid search for hyperparameters tuning.*
4. Saving the best model


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. run the download_titanic.sh script to download the data
```
    ./download_titanic.sh
```
    
3. Create a virtual env in the project folder (for help see this [tutorial](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/))
4. Run the following command to install the necessary packages
* For linux users:
```
pip3 install -r requirements.txt
```
* For windows users:
```
pip install -r requirements.txt
```


5. Open the pyspark.ipynb notebook and run the cells.<br> 
*Please choose the python virtual environment you created previously*


*Note: Make sure you have Java installed on your computer, because spark*


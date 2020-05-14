# Predicting Bike Sharing Patterns
* This project was a part of Udacity Deep Learning Nano Degree.
* Built a Neural Network without using any framework(only Numpy) to predict Bike sharing Patterns.
* Used Bike sharing patterns Dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset) 

## Requirements
* If you don't have python installed on your machine download it from [here](https://www.python.org/ftp/python/3.8.2/python-3.8.2.exe)
* Then install pip on your machine by downloading this [get-pip.py](https://bootstrap.pypa.io/get-pip.py) and from the downloads directory 
run ```python get-pip.py```
* To start working on the project run the following command after cloning the repository.
```
pip install -r requirements.txt
```
* I suppose Anaconda is already installed in the machine. Then run the following command
```
conda install pytorch torchvision -c pytorch
```
* This would install all the requirements.
## Output
* This dataset contains the hourly and daily count of rental bikes between years 2011 and 2012 in Capital bikeshare system with the corresponding weather and seasonal information.
* Did some preprocessing on the data,
* Trained the neural network using all the data except the last 21 days
* Tested the neural network by predicting the data for the last 21 days. Below image displays the plot between Predicted and Original Data.
* For Further Information see the [notebook](https://github.com/saisrirammortha/Predicting-Bike-Sharing-Patterns-/blob/master/Your_first_neural_network.ipynb)
![Output Image](https://github.com/saisrirammortha/Predicting-Bike-Sharing-Patterns-/blob/master/output.png)



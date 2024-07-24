# Traffic sign classification

-A machine learning model trained using CNN that classifies traffic signs from images.
-Technologies used : Python libraries like tensorflow, keras, sklearn, matplotlib, pandas, pil and tkinter.

# Dataset

[Download GTSRB Dataset](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

The dataset contains more than 50,000 images of different traffic signs. It is further classified into 43 different classes. 
The dataset is quite varying, some of the classes have many images while some classes have few images. The size of the dataset is around 300 MB.
The dataset has a train folder which contains images inside each class and a test folder which we will use for testing our model.

To install necessary packages to run the project use "pip install tensorflow keras sklearn matplotlib pandas pil".

Extract dataset files into the project folder and run the script file "traffic_sign.py" to train the model. The model will be saved as "my_model.h5" in the same directory.

Run the "gui.py" file to launch the project.


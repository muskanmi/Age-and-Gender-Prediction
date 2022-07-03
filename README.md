# DIGIT RECOGNIZER

Age and Gender prediction is a simple flask application which can be used to recognize the Gender of the human being present in an image as well as his/her age.


## Instructions


### Training of the Model:

1. You can see the code for training the model in this [notebook](https://github.com/muskanmi/Age-and-Gender-Prediction/blob/master/training/age-gender-training.ipynb).

2. Before running the code for training the model, you need to have the **dataset** downloaded and placed inside the [training](https://github.com/muskanmi/Age-and-Gender-Prediction/tree/master/training) folder.  
You can download the dataset from Kaggle present [here](https://www.kaggle.com/datasets/jangedoo/utkface-new).

3. This repository also consists of already trained weights for this model which you can find [here](https://github.com/muskanmi/Age-and-Gender-Prediction/blob/master/src/data.h5).


### Running the application:

1. Get the source code on your pc via git.

```shell
  git clone https://github.com/muskanmi/Age-and-Gender-Prediction.git
```

2. Create a virtual environment to install the required dependencies of the application.

```
  virtualenv venv
```

3. Activate the virtual environment (You have to activate it every time you are working on project).

```
  For mac users:

    source venv/bin/activate  

  For windows users:

    .\venv\Scripts\activate

  For Linux users:

    source venv/bin/activate
```

4. Now, install python dependencies.

```
  pip install -r requirements.txt
```

5. Now, navigate to the **src** directory (containing the **app.py** file).

6. Run following command:

```
  python app.py
```

7. Application is ready for use. You can run it at [http://localhost:80/](http://localhost:80/).

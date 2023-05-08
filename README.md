# gender-prediction-based-on-voice


This machine learning project is aimed at predicting the gender of a speaker based on their voice characteristics. The project uses the Sci-kit Learn library in Python to build and train a classification model using the voice dataset.

## Dataset

The dataset used for this project is the [Voice Dataset](https://www.kaggle.com/primaryobjects/voicegender) from Kaggle. It consists of 3168 recorded voice samples, where each sample is labeled as either male or female. The dataset includes several acoustic features such as mean frequency, standard deviation of frequency, and spectral entropy, which are used as input features for the classification model.

## Requirements

To run this project, you will need:

- Python 3.x
- Sci-kit Learn library
- Pandas library
- Numpy library

You can install the required libraries using pip:

```bash
pip install scikit-learn pandas numpy
```

## Usage

To use this project, you can follow these steps:

1. Clone the repository

```bash
git clone https://github.com/ParthKalkar/gender-prediction-based-on-voice
```

2. Navigate to the project directory

```bash
cd gender-classification
```

3. Run the `gender_classification.py` script

```bash
python gender_classification.py
```

This will train the classification model using the dataset and test it on a random sample of the data. The model's accuracy will be displayed on the console.

## Results

After running the `gender_classification.py` script, the classification model will be trained and tested on a random sample of the dataset. The accuracy of the model will be displayed on the console. The output should look like this:

```
Accuracy: 98.7%
```

## Future Work

There are several ways in which this project can be extended or improved:

- Experiment with different classification algorithms such as Decision Trees or Random Forests
- Use more advanced feature engineering techniques to improve the accuracy of the model
- Explore the dataset further to gain more insights into the gender classification problem

## Credits

This project was developed by Parth Kalkar. The Voice Dataset used in this project is available on [Kaggle](https://www.kaggle.com/primaryobjects/voicegender).

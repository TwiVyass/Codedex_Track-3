# Track 3: Predict 2024 Olympics Champion

## Challenge
The Codedex challenge stated to analyze 2021 Tokyo Olympics dataset to predict who wins 2024 Paris Olympics!
The Tokyo 2020 Summer Olympics, which took place in 2021 due to the COVID-19 pandemic, left a lasting impact.
1. Tokyo 2020 introduced new sports like skateboarding, surfing, sport climbing, and breaking (a dance-based sport). These additions brought fresh energy to the Olympic stage during a period of uncertainty.
2. The Tokyo 2020 Games included athletes from countries like Turkmenistan and San Marino who won their first-ever Olympic medals.

The Paris 2024 Summer Olympics, which will be hosting the world's top athletes from July 26 to August 11, have faced definitely more interesting coverage with regard to the location that they are taking place in. Besides that, notable changes include:

1. Paris 2024 will feature 28 returning sports, along with four exciting additions: sport climbing, skateboarding, surfing, and breaking. Breaking, in particular, will make its Olympic debut.
2. In a historic decision, the International Olympic Committee awarded both Paris (2024) and Los Angeles (2028) the hosting rights simultaneously.

## Technologies used
- Python, Kaggle
- Google Colab

## Thought process: 
1. Attempting to find a correlation between sports that are common to both Paris 2024 and Tokyo 2020 Olympics to predict which sport is likelier to cause a victory in 2024.

2. The events dataset is merged with the athletes dataset based on the 'sport' and 'Discipline' columns to form an educated dataset.

3. The resulting dataset is then merged with the medal count data to form an appropriate training dataset.

4. The final merged dataset combines events from Paris 2024 with athlete counts from Tokyo 2020.
   
5. The results are:
Logistic Regression and Support Vector Classifier (SVC) achieved an accuracy of about 36%.
Random Forest's results were heavily overfit.



## Datasets
- [Tokyo 2021 Olympics dataset: Kaggle](https://www.kaggle.com/)
- [Paris 2024 Olympics dataset: Kaggle](https://www.kaggle.com/)

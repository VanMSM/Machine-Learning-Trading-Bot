
# MACHINE LEARNING TRADING BOT

___

## Background

This project assumes the role of a financial advisor at one of the top five financial advisory firms in the world. The firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, it has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave the firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, this project will enhance the existing trading signals with machine learning algorithms that can adapt to new data.




---

## Project Sections

* Baseline Performance

* Baseline Trading Algorithm

* New Machine Learning Classifier

* Evaluation Report

BASE MODEL PLOT:

<img width="590" alt="Screen Shot 2021-07-11 at 7 25 31 PM" src="https://user-images.githubusercontent.com/80144026/125224545-ad891480-e282-11eb-8b21-af42760801ab.png">

NEW MACHINE LEARNING MODEL PLOT

<img width="590" alt="Screen Shot 2021-07-11 at 7 31 22 PM" src="https://user-images.githubusercontent.com/80144026/125224562-b679e600-e282-11eb-8288-0435cf97f9ae.png">

Analysis:

* Did this new model perform better or worse than the provided baseline model? The Base model performs better than the Logistic Regression Model since it has a higher accuracy score.

* Did this new model perform better or worse than your tuned trading algorithm? The new model performs worse than the base model.

* What impact resulted from increasing or decreasing the training window?

ANSWER: Increasing the training window from 3 months to 8 months impacted the accuracy of the algprithm.

* What impact resulted from increasing or decreasing either or both of the SMA windows?

ANSWER: Upon increasing the SMA short window from 4 to 50, the macro avg accuracy score dropped from .82 to .31 and the weighted average from .77 to .38  

* Choose the set of parameters that best improved the trading algorithm returns.

For the SVM Model, it performs better with SMA Windows of 4 and 100 days and training window of 3 months

<img width="589" alt="Screen Shot 2021-07-11 at 8 29 30 PM" src="https://user-images.githubusercontent.com/80144026/125226948-d7dcd100-e286-11eb-93f4-73d9dcdd8b0d.png">

For the Logistic Regression, the trading algorithm perfoms better with SMA Windows of 4 and 100 and a longer training window, in this case I used 8 months.

<img width="589" alt="Screen Shot 2021-07-11 at 8 34 10 PM" src="https://user-images.githubusercontent.com/80144026/125227253-67827f80-e287-11eb-96cf-50bb006f20c8.png">

<img width="589" alt="Screen Shot 2021-07-11 at 8 34 17 PM" src="https://user-images.githubusercontent.com/80144026/125227263-6b160680-e287-11eb-99a9-180884847ddc.png">


---

## Technologies

This project is written in Python with the following packages:

* Numpy
* Pandas
* scikit-learn

---

## Installation Guide

Before running the application first install and verify the following dependencies:

* Pandas from PyPI
```python
pip install pandas
```
* Numpy from PyPI
```python
pip install numpy
```

Next, Import the Modules

```python
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
```

Clone to your repo and run

---



## Contributors

[Van Miller Sarcov Maquilan](https://www.linkedin.com/in/van-miller-sarcov-maquilan-20b472202/) 


---

## License

Feel free to add to this code, and use for your own project. :)

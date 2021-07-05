
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

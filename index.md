```python
#!pip install textblob
#!pip install torch
#!pip install praw
from textblob import TextBlob
import torch
import torch.nn as nn
import torch.optim as optim
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import Lasso, LogisticRegression
import sklearn.metrics as metrics
from sklearn.model_selection import train_test_split
from tqdm import tqdm
from pprint import pprint
import numpy as np
import praw
import pdb
import warnings
warnings.filterwarnings("ignore")
```

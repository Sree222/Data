# finalCapstone
# Machine learning - PCA of UsArrests dataset  
In this task, we explore the arrests based on different types of crimes in various cities using unsupervised learning methods such as Principal Component Analysis (PCA) and
various clustering techniques. The dataset we will be exploring contains data on 50
states. There are 4 variables for each city in total, with 4 describing the crime incidents in each state.

## Table of Contents

- [About](#about)
- [Getting Started](https://github.com/Sree222/finalCapstone/new/main?readme=1#getting-started)
- [UsArrests - machine learning](https://github.com/Sree222/finalCapstone/new/main?readme=1#usarrests---machine-learning)
- [Installing](#installing)
- [Usage](#usage)
- [Contributing](#contributing)

## About
This dataset is from the US Arrests Kaggle challenge (https://www.kaggle.com/datasets/kurohana/usarrets). A description of the data is given as: “This data set contains statistics, in arrests per 100,000 residents, for assault, murder, and rape in each of the 50 US states in 1973. Also given is the percent of the population living in urban areas.”

## Getting Started

To run this project, import libraries:

- import numpy as np
- import pandas as pd
- import seaborn as sns
- import matplotlib.pyplot as plt
- from sklearn.preprocessing import StandardScaler
- from sklearn.decomposition import PCA

## UsArrests - machine learning

To generate an in-depth PCA report of the dataset UsArrests.csv downloaded from kaggle, and to explore and interpret the outcomes of any analyses.

Next images are just some examples of the results in the data exploration.

- **_Exploring the dataset_**

Crimes correlation *Note that the crimes are not correlated with population living in urban areas.

  ![image](https://user-images.githubusercontent.com/91984156/217934990-48eff24a-bf24-4f32-846c-d852311c1a11.png)

- **_Apply PCA_**

Cumulative variance plot

![image](https://user-images.githubusercontent.com/91984156/217935679-3a6a1a02-f8de-4a11-a521-743cab8dbcce.png)

Scree plot

![image](https://user-images.githubusercontent.com/91984156/217935853-1d2554fb-98dc-459a-874b-a4926a94c49a.png)

- **_Cluster Analysis_**

Hierarchial clustering

![image](https://user-images.githubusercontent.com/91984156/217936191-081bc7b8-04c2-4254-a041-67cc81f02d56.png)

K- means clustering

![image](https://user-images.githubusercontent.com/91984156/217936337-46809b04-5e69-4a6e-a398-d1cf322300c2.png)




## Installing
Installation instructions.

## Usage
A step by step series of examples that tell you how to get a development env running.

## Contributing
Contributors names.
```

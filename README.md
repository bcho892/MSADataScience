## Part 1 - Exploratory Data Analysis (EDA):
Before doing any processing on the data, it is essential that a data scientist has to know at least the general format of the data and the statistics of said data.

You are expected to show at least the following without hard-coding the values:

Numerically:
- [X] Average.
- [X] Standard Deviation.
- [X] Percentile range either:
    - [ ] 10th and 90th or
    - [X] 25th and 75th.

Graphically:
- [X] Correlation Plot.
- [X] Graphing any Numerical Sections of the dataset.

In addition:
- [X] Comment on the dataset that is provided to you based on the EDA.

You are also to convert any columns to their appropriate types when required.

## Part 2 - Data Preparation:
Now that you know your data inside and out, you are to clean the dataset by removing any unused values and make the dataset usable to train the model.

Note that the models used in the next section only understand numbers.

Student Checklist:
- [X] Data deemed useless removed.
- [X] Dataset converted to a form that a model can use.
- [X] A train and test dataset for the model made.
- [X] State a reason for each changes made to the DataFrame.

Ensure that you have also show some general information of the train/test dataset like in the EDA before entering the modelling stage.

## Part 3 - Data Modelling:
With the dataset made, you are to choose a model best suited for your purpose of the goal. There are a good number of models to choose from in the sci-kit learn library.

After training the model, you are required to have the model predict one month after the latest date in the dataset and comment on the results.

Student Checklist:
- [X] Model selected.
- [X] Training dataset fitted.
- [X] Testing dataset scored.
- [X] Another month of the existing dataset predicted.
- [X] Model evaluation in a paragraph.

## Passing this section:

In order to pass Phase 2, you are required to carry out all 3 parts of this section. Any interesting observations should be noted, especially in the first and third parts of this section.

You are **NOT** required to achieve a very accurate model to pass phase 2, but it is recommended that you try and aim for higher accuracy scores.

## Resource Information:
* [Matplotlib](https://matplotlib.org/) - A library for generating graphs.
* [Pandas](https://pandas.pydata.org/docs/reference/index.html) - A library to handle dataset operations and getting statistics.
* [Sci-kit Learn](https://scikit-learn.org/stable/) - Beginner friendly library where models can be used.
* [Seaborn](https://seaborn.pydata.org/) - Extensive library to plot more graphs. Extends from matplotlib.

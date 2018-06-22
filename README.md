
## Project: Titanic Survival Exploration


### Install

This project requires **Python 3.X** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 3.X installer and not the Python 2.7 installer.

### Code

Template code is provided in the notebook `titanic_survival_exploration.ipynb` notebook file. Additional supporting code can be found in `visuals.py`. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory titanic_survival_exploration/ (that contains this README) and run one of the following commands:

```
git clone https://github.com/cakmakaf/titanic_survival_exploration.git
```

This will open the Jupyter Notebook software and project file in your web browser.

### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the features of the passengers, such as name, sex, age, etc.

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)

### Description

In this optional project, we will create a decision functions to predict survival outcomes from the 1912 Titanic disaster based on each passenger’s features. We start with a simple classification and increase the algorithm's copmlexity until the accuracy hits to 80% at least. 

The project provides us an idea about one of the fundamental concepts of machine learning such as decision tree and we apply
decision trees to implement results out of the data.

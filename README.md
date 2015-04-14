# Predicting NFL and College Football Champions

### Summary
The goal of this project is to build machine learning models to predict the winners of 2015 Super Bowl and the College Football Championship using historical game data.

We have predicted the outcome of football matches entirely using the knowledge of previous game statistics. We have used three different models to do this:

1. **Baseline model**:  `Point Score Difference Model`. In this model we use the score difference to predict winners of future games.
2. **Linear Regression Model**: In this model, we use linear regression to predict the point difference for each game.
3. **PageRank Model**: Here, we model the game data as a graph with nodes as teams and edges as score differences between the teams. We then use PageRank on this game graph to rank all the teams. This ranking is used to predict winners of future games.

###### Winner Predictions:
- Super Bowl: Seattle Seahawks
- College Champions: Oregon

#### Code
Most files are IPython notebooks (`.ipynb` extension with JSON data).

The following modules are used in at least one example:

  * Python 2.7
  * NumPy
  * Pandas
  * Scipy
  * scikit-learn
  * NetworkX
  * nltk
  * seaborn
  * Matplotlib
  * IPython 0.13+
  * cPickle

You can view the notebooks in the IPython notebook viewer (see links below).

* Baseline Models:
  * Baseline 1: [NFL](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/nfl/nfl_baseline_1.ipynb) | [College](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/college_football/clg_baseline_1.ipynb)
  * Baseline 2: [NFL](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/nfl/nfl_baseline_2.ipynb) | [College](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/college_football/clg_baseline_2.ipynb)
* Linear Regression Models:
  * Paired Features: [NFL](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/nfl/nfl_linear_regression_paired_version.ipynb) | [College](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/college_football/clg_linear_regression_paired_version.ipynb)
  * Separate Features: [NFL](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/nfl/nfl_linear_regression_separate_version.ipynb) | [College](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/college_football/clg_linear_regression_separate_version.ipynb)
  * Helper Notebooks: [NFL](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/tree/master/nfl) | [College](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/tree/master/college_football)
* Page Rank Models:
  * Page Rank: [NFL](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/nfl/nfl_pagerank.ipynb) | [College](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/blob/master/college_football/clg_pagerank.ipynb)
* Initial Models: [Notebooks](http://nbviewer.ipython.org/github/chetannaik/predict-nfl-champions/tree/master/old_notebook_files/)

#### Team Members:
- Chetan Naik
- Ankit Arun
- Sindhuri Mamidi
- Beijie Li

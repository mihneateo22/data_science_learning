# Data Science Learning

My path through Jake VanderPlas's *Python Data Science Handbook* (2nd ed.),
with a project of my own built alongside it.

The book covers IPython, NumPy, Pandas, Matplotlib/Seaborn and Scikit-Learn.
The project grows as I read: every chapter's tools show up in it as soon as I've learned them,
from loading and cleaning the data through exploratory analysis to a first machine learning model.

## Project

*To be chosen.* The question, dataset and findings will go here.

## Repo layout

    data/raw/     original data, never edited by hand
    notebooks/    one notebook per stage (01_numpy.ipynb, 02_pandas.ipynb, ...)
    src/          reusable functions pulled out of notebooks
    LOG.md        learning log, one entry per session

## Setup

    python -m venv .venv
    source .venv/bin/activate        # Windows: .venv\Scripts\activate
    pip install numpy pandas matplotlib seaborn scikit-learn jupyter

## Resources

- [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) (`notebooks_v2`)
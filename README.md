
# Botmock User Behavior Analysis

#### -- Project Status: Active

## Project Intro/Objective
This project is a deep dive into Botmock user behavior, with the ultimate goal to be identification of the AHA moment.


### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python
* MySql
* Pandas, jupyter


## Project Description
> Aha is the moment that the utility of the product really clicks for the users; when the users really get the core value —
> what the product is for, why they need it, and what benefit they derive from using it.
>> — Sean Ellis

As engineers, product managers, and marketers, we know our product's value propositions the way we know our own birthdays. However, what's obvious to us is not always obvious to our users, causing unintentional dishonesty in qualitative studies, and even more difficult to identify with ony a basic understanding of user behavior on our app.

The goal of this project is to turn usage data into something tangible and actionable. It's not just about *what* the magic moment is for the user but *when* and *how*. A common example is Facebook-- their growth team mined and analyzed user data to identify that users find value in their product when they connect with ten friends within seven days.

	!(images/facebook-aha.png)

The illustration above shows the sweet spot between users who performed the action and retained vs. users who retained that performed the action. This is the tipping point for most users-- when the *what* becomes the *how many*. After finding out *when* the user must perform the action, we'll run validation tests and experiments to prove our hypothesis.

## Needs of this project

- frontend developers
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- etc. (be as specific as possible)

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

*If using offline data mention that and how they may obtain the data from the group)*

3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Author and Contact Information
Allison Kelly
Data Scientist & Digital Marketing Consultant
203.848.0545 | allison@botmock.com | [Github Profile](https://www.github.com/akelly66) | [Linkedin](https://www.linkedin.com/in/akelly66)

#### Other Members:


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

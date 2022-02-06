# Churn predictive model

> This project was developed using Deepnote. You can click the button below and interact with files.

[<img src="https://deepnote.com/buttons/launch-in-deepnote.svg">](https://deepnote.com/project/churnpredictivemodel--y7FXq2oTeST3i0F8jbBOw/%2Fchurn_predictive_model%2FREADME.md)

## Who will stay 2 years or more?

The purpose of this analysis is to identify (and predict) customers who will stay 2 years or more. This is important
since the company (Kin Security) must profit. A commercial campaign may be created based on this analysis.

The model used is **Logistic Regression**. The process followed is:

* Cleaning dataset according to desired population. See `notebooks/0.1-axel-exploration.ipynb`.
* EDA in order to understand data. See `notebooks/0.2-axel-exploration.ipynb` and `notebooks/0.3-axel-exploration.ipynb`.
* Feature engineering. Normalization and encoding. See `1.1-axel-modeling.ipynb`.
* Modeling. Logistic regression model. See `1.2-axel-modeling.ipynb`.

## The data

Raw data were too large and you won't see them on GitHub. For your convenience, an auxiliar directory was created on which
cleaned and processed data is stored. See `data_sent_github`.

On the other hand, if you launch the project on Deepnote, you will be able to see raw data.

[<img src="https://deepnote.com/buttons/launch-in-deepnote.svg">](https://deepnote.com/project/churnpredictivemodel--y7FXq2oTeST3i0F8jbBOw/%2Fchurn_predictive_model%2FREADME.md)


## Project organization
```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling. (Too large for GitHub)
│   └── raw            <- The original, immutable data dump. (Too large for GitHub)
│
├── data_sent_github   <- Processed data sent to GitHub. Contains the same as data/processed
├── reports            <- Project report
│   └── report_churn_model.pdf 
│
├── notebooks          <- Jupyter notebooks. Naming convention: number (for ordering),
│   ├── 0.1-axel-exploration.ipynb     
│   ├── 0.2-axel-exploration.ipynb        
│   ├── 0.3-axel-exploration.ipynb
│   ├── 1.1-axel-modeling.ipynb
│   └── 1.2-axel-modeling.ipynb
│
└── requirements.txt   <- The requirements file for reproducing the analysis environment.

```
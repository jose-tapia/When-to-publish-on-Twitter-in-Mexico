# When to publish on Twitter in Mexico

This repository contains the dataset of users and tweets from a certain poblation described on the FPA of Data Analytics course. It includes the Jupyter Notebook that process the tweets to retrieve information.

We uses the modules [pysentimiento](https://pypi.org/project/pysentimiento/) and [WhatTheLang](https://pypi.org/project/whatthelang/) to pre-process the tweets, retrieve more information as the sentiment and emotion, as well as detect the language of the tweet.

The datasets are available in Kaggle: https://www.kaggle.com/code/jmtapiaavitia/preliminary-analysis-when-to-tweet-in-mexico (accessed on August 6, 2022).

Authors: _José Manuel Tapia-Avitia, Carlos Alonzo López Castañeda, Francisco Javier Cantú Ortiz

## Requirements

- Python v3.7+
- Standard modules: matplotlib, numpy, pandas, scipy.stats, seaborn

## Files

- **Main notebook**: [processing_results_tweets.ipynb](./processing_results_tweets.ipynb)
- Raw figures generated from the main notebook: [figures/](./figures/)
- Raw dataset of 21,000 users described on the FPA: [users_dataset.csv](./datasets/users_dataset.csv)
- Pre-processed dataset of 11,781 tweets from a small selection of users: [tweets_users.csv](./datasets/tweets_users.csv)

## Contact information

José Manuel Tapia-Avitia - [A00834191@tec.mx](mailto:A00834191@tec.mx)

Carlos Alonzo López Castañeda - [A01378902@tec.mx](mailto:A01378902@tec.mx)

Distributed under the MIT license. See [LICENSE](./LICENSE) for more information.

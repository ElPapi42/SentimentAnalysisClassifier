# SentimentAnalysisClassifier
Sentiment Classifier for IMDB Review Dataset

This Experiment show all the process done for reach some close SotA on sentiment analysis using IMDB Dataset. From EDA to Model Definition And Fitting. The Dataset was divided in 3 parts, Training(45k examples), Evaluation(2.5k examples) and Test(2.5k examples) sets. The model architecture features LSTM + Dense Networks, slightly regularized and Batch Normalized.

The next link, redirect to Weights And Biases web page, where was logged the experiments results: https://app.wandb.ai/elpapi42/Sentiment-Analysis-Classifier?workspace=user-elpapi42

This link is for an general architecture overview: https://www.plectica.com/maps/NMR0B1AZT

There exist 4 of the most relevant runs of the Model during experiments. proud-tree-81 was the iteration with the best performance on test, Reaching 99.4% Accuracy and minimun variance from Evaluation To Training set: https://app.wandb.ai/elpapi42/Sentiment-Analysis-Classifier/runs/c6o93kl3?workspace=user-elpapi42

If you cant see the notebook due to GitHub issues, check this: https://nbviewer.jupyter.org/github/ElPapi42/SentimentAnalysisClassifier/blob/master/SentimentAnalysisClassifier.ipynb

References:

Original Paper Presenting IMDB Reviews Dataset:

Maas, Andrew L. and Daly, Raymond E. and Pham, Peter T. and Huang, Dan and Ng, Andrew Y. and Potts, Christopher
Learning Word Vectors for Sentiment Analysis
Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies
June 2011
Portland, Oregon, USA
Association for Computational Linguistics
Pages: 142-150
http://www.aclweb.org/anthology/P11-1015

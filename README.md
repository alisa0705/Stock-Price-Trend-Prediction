# Stock Price Trend Prediction
The movement in the stock market is affected by lots of factors including inflation and interest rates, international events, and financial reports directly and indirectly. The latest revealed news and information could impact investors’ demand for stocks and thus become influential to the stock price. Therefore, in this project, we focus on a document classification NLP problem. More specifically, we conducted sentiment analysis by using daily news headlines to predict stock market movement. Two stock market prediction models were established and compared as a result.


For this project, we trained both the Naive Bayes model (the generative probabilistic model) and the LSTM model (the discriminative neural network) to perform sentiment analysis to predict stock market movement using the daily news headlines dataset. These two approaches are applied to both the real-world data and the synthetic data generated from the Naive Bayes model. In conclusion, in both “real” data and synthetic data cases, our Naive Bayes model performs better than the LSTM model in terms of higher model accuracy and lower model complexity in terms of time and space.

Confusion Matrix of Naive Bayes Model and LSTM Model:
<img width="817" alt="Confusion Matrix of Naive Bayes Model and LSTM Model for Real-world Data" src="https://user-images.githubusercontent.com/89174034/220716578-d9a72823-6e71-44b3-8df7-7072f6abcf88.png">


Accuracy of LSTM Model for Real-world Data:
<img width="570" alt="Accuracy of LSTM Model for Real-world Data" src="https://user-images.githubusercontent.com/89174034/220716839-1c88967b-7f4d-45e2-9a51-d8ab964cf502.png">

### References
C.D. Manning, P. Raghavan and H. Schuetze (2008). Introduction to Information Retrieval. Cambridge University Press, pp. 234-265. Retrieved Dec 11, 2022, from https://nlp.stanford.edu/IR-book/html/htmledition/naive-bayes-text-classification-1.html
Scikit-learn: Machine Learning in Python, Pedregosa, et al., JMLR 12, pp. 2825-2830, 2011.
Sun, J. (2016, August). Daily News for Stock Market Prediction. Kaggle. Retrieved November 16, 2022, from https://www.kaggle.com/aaron7sun/stocknews

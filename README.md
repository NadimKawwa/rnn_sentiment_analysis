# SageMaker Deployment Project

In this repository we will go through the exercise of deplying a sentiment analysis model on AWS SageMaker.
To to do we will use the [IMDb dataset](https://ai.stanford.edu/~amaas/data/sentiment/). 
![reviews](https://github.com/NadimKawwa/rnn_sentiment_analysis/blob/master/test_website_pics/reviews_ex.png)

To determine the sentiment of reviews we use a recurrent neural network (RNN). The picture below shows a sample architecture.
![network](https://github.com/NadimKawwa/rnn_sentiment_analysis/blob/master/test_website_pics/network_diagram.png)

The project begins with collecting the data, cleaning it in a readable format, and running some tests within the notebook.
Next we deploy the model to a web app using AWS's Lambda. The sketch below shows the interaction between the app and the deployed model.
![api_sketch](https://github.com/NadimKawwa/rnn_sentiment_analysis/blob/master/Web%20App%20Diagram.svg)

With our model deployed, we can access the URL associated with the endpoint. The plot below shows a sample review.
![pos_sample](https://github.com/NadimKawwa/rnn_sentiment_analysis/blob/master/test_website_pics/pos_sample.png)

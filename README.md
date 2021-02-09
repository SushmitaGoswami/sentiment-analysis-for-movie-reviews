# Sentiment-analysis-for-movie-reviews
Sentiment analysis for movie reviews Project is a part of Udacity Deep Learning Nanodegree.

# Project Overview
The prediction model is implemented in PyTorch and deployed to AWS SageMaker. It's a deployed web page which defines sentiment of a movie review.
To serve it on a web page, it is being configured and called from a AWS Lambda service, which can be accessed via API Gateway.

# Sample result
Following are some of the sample result based on some sample moview reviews.

### Positive review
![Alt text](src/images/positive.PNG?raw=true "positive review")

### Negative review
![Alt text](src/images/negative.PNG?raw=true "negative review")

# Technology Used
- Python Frameworks (NumPy, Pytorch, OpenCV, Matplotlib, etc.)
- Long short-term memory
- Amazon Services (AWS SageMaker, Amazon API Gateway, AWS Lamda, Amazon S3, XGBoost notebook)




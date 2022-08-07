# PCA Mnist Model sample

This example notebook shows how to use PCA model for the Mnist dataset.

It demonstrates the following:
* Basic setup for using SageMaker.
* converting datasets to protobuf format used by the Amazon SageMaker algorithms and uploading to user provided S3 bucket. 
* Training SageMaker's XGBoost algorithm on the data set.
* Training SageMaker's Linear Learner on the data set.
* Hosting the trained models.
* Scoring using the trained models.

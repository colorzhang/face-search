## Face search demo using Amazon ES knn and machine learning.

High level steps:

1. face detection and feature extraction
2. feature vector index in ES
3. 1:N vector search

Prerequisites:
* face_recognition, https://github.com/ageitgey/face_recognition
* Amazon ES (Cloud) 7.1+ or Open Distro for Elasticsearch (On promise) 1.8+
* Amazon Rekognition (Optional)

References:
* Visual image search, https://aws.amazon.com/blogs/machine-learning/building-a-visual-search-application-with-amazon-sagemaker-and-amazon-es/

Architecture:

![architecture](https://github.com/colorzhang/face-search/blob/master/arch.png)

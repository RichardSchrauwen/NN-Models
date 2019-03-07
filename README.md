# NN-Models & SageMaker Deployment

## Neural Network Model Deployment

Use of Amazon Sagemaker to build, test and deploy neural networks. 

Notebook XGBoost (Batch Transform) contents:
- A model is trained first
- A transformer is made
- Perform a batch transform job

How to test with an external application:
- Create a HTTP POST endpoint (API) in API Management
- Create test application to use the endpoint (url)
- or use the index.html and insert the url in there

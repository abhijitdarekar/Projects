# Kubeflow Emoji Pipeline
#### Demonstrates working of simple kubeflow pipeline on vertex AI.

To Run the kubeflow pipeline on Vertex ai (GCP), below are the required api's to be enabled.
1. AiPlatform Api
2. Compute Api
3. Container Registery


We need a create a new bucket or folder in existing bucket to store the metadata realted to training pipeline.

Service Account of project should have full access to bucket.
# Model Serving Examples

## Items created and running successfully

##### Namespace: ai-example-multi-serving-model
* Successful Job: create-buckets-multi-model-*
* Successful Job: upload-model-to-s3-multi-model-*
* ConfigMap: upload-model-to-s3-multi-model
* ConfigMap: create-bucket-multi-model
* Secret: aws-connection-multi-model

* Pod: modelmesh-serving-multi-model-server-*
* InferenceService: fraud-detection-model
* ServingRuntimes: multi-model-server
* Deployment: modelmesh-serving-multi-model-server
* Route: fraud-detection-model
* Service: modelmesh-serving

* Pod: minio-*
* Secret: minio
* Deployment: minio
* Route: minio-api
* Route: minio-ui
* Service: minio

##### Namespace: ai-example-single-serving-model
* Successful Job: create-buckets-tgis-*
* Successful Job: upload-model-to-s3-tgis-*
* ConfigMap: create-bucket-tgis
* ConfigMap: upload-model-to-s3-tgis
* Secret: aws-connection-tgis
* InferenceService: tgis
* ServingRuntime: tgis
* Deployment: tgis-predictor-*-deployment
* Pod: tgis-predictor-*-deployment

* Successful Job: create-buckets-vllm-*
* Successful Job: upload-model-to-s3-vllm-*
* ConfigMap: create-bucket-vllm
* ConfigMap: upload-model-to-s3-vllm
* Secret: aws-connection-vllm
* InferenceService: vllm
* ServingRuntime: vllm
* Deployment: granite-predictor-*-deployment
* Pod: granite-predictor-*-deployment

* Pod: minio-*
* Secret: minio
* Deployment: minio
* Route: minio-api
* Route: minio-ui
* Service: minio

##### Namespace: isto-system
* Route: granite-ai-example-single-model-serving
* Route: tgis-ai-example-single-model-serving

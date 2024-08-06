# FromSagemakerToUltralitics


This is a tool or will be a series of tools that can help you to map Sagemaker with Ultralitics.

## How to format a Dataset from Sagemaker Ground of Truth to Ultralitics?

The Notebook "dataset_to_yolo" will go throw the process of converting the output from Sagemaker Ground of Truth to Ultralitics format.

During the process of conversion if you want to adapt it to your environment, keep in mind that this Notebook was build in Sagemaker Notebook inside Sagemaker Studios. Therefore, the IAM policies need to gather the results from S3 were skiped from the notebook, since Sagemaker Studio already had those access permissions.

Moreover, all the directory path and buckets name should change based on your environment.

Hope this guide/Notebook can help you 😎

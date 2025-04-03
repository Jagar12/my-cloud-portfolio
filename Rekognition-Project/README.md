AWS Rekognition with S3

Overview

This project demonstrates how to use AWS Rekognition to detect labels in images stored in an S3 bucket. The guide walks through setting up an S3 bucket, installing and configuring AWS CLI, and running a Python script to analyze images using Rekognition.

Prerequisites

An AWS account

AWS CLI installed and configured

Python installed (preferably Python 3.x)

Required Python libraries: boto3, matplotlib, PIL

Steps to Set Up

1. Create an Amazon S3 Bucket and Upload Images

2. Install and Configure AWS CLI

3. Install Required Python Libraries

4. Run the Python Script


Replace image_file_name and bucket_name with your actual values.

Run the script:

python script_name.py

Expected Output

A list of detected labels along with confidence levels.

A pop-up displaying the image with bounding boxes around detected objects.

Best Practices

Do not hardcode access keys in the script.

Rotate and manage AWS credentials securely.

Enable least privilege access for IAM users.

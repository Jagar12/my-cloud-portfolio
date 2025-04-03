# AWS Rekognition with Amazon S3

## Project Overview
This project demonstrates the integration of **Amazon Rekognition** and **Amazon S3** using **Python**. You will learn how to create an S3 bucket, upload images, and use Rekognition to detect objects and labels in the images through a Python script.

## Prerequisites
- Active AWS Account
- AWS CLI (Installed & Configured)
- Python 3.x Installed
- Python packages: `boto3`, `matplotlib`, `Pillow`

## Setup Instructions

### Step 1: Create an Amazon S3 Bucket and Upload Images


### Step 2: Install and Configure the AWS CLI


### Step 3: Install Required Python Libraries
Install the necessary dependencies:
```sh
pip install boto3 matplotlib Pillow
```

### Step 4: Python Script to Detect Labels with Rekognition
Create a Python file (e.g., `detect_labels.py`) and paste the following code:


### Step 5: Execute the Script
In your terminal, navigate to the script directory and run:
```sh
python detect_labels.py
```

## Output
- Printed list of detected labels with confidence scores.
- Visual display of the image with labeled bounding boxes.

## Security Best Practices
- **Never hardcode credentials in your code.**
- Use **IAM roles** or **AWS credentials file**.
- Follow the **principle of least privilege**.
- **Rotate** your credentials regularly.


Feel free to contribute or raise issues to enhance this project!


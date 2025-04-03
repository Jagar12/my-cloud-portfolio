# AWS Rekognition with Amazon S3

## Project Overview
This project demonstrates the integration of **Amazon Rekognition** and **Amazon S3** using **Python**. You will learn how to create an S3 bucket, upload images, and use Rekognition to detect objects and labels in the images through a Python script. Rekognition was a product I was very excited to gain experience with. There are an endless amount of applications for this service, so I was eager to delve in. In this project, I set out to build an image labels generator that will be able to recognize and label images. 

## Prerequisites
- Active AWS Account
- AWS CLI (Installed & Configured)
- Python 3.x Installed
- Python packages: `boto3`, `matplotlib`, `Pillow`

## Services Used
- S3, Amazon Rekognition, Lambda, IAM, AWS CLI.

## Setup Instructions

### Step 1: Create an Amazon S3 Bucket and Upload Images


### Step 2: Install and Configure the AWS CLI


### Step 3: Install Required Python Libraries


### Step 4: Python Script to Detect Labels with Rekognition


### Step 5: Execute the Script


## Output
- Printed list of detected labels with confidence scores.
- Visual display of the image with labeled bounding boxes.

## Security Best Practices
- **Never hardcode credentials in your code.**
- Use **IAM roles** or **AWS credentials file**.
- Follow the **principle of least privilege**.
- **Rotate** your credentials regularly.

  ## Final Statement
  -This project was a lot of fun and taught me some valuable skills to be used with the Rekognition project, the AWS CLI, as well as a reminder of how many background services (such as IAM, S3, and Lambda) are utilized for each and every project. I am also excited for the opportunity to explore the Rekognition project further. Some future applications that I hope to explore are adding video label detection, real-time object label detection and analyzing facial expressions. 


Feel free to contribute or raise issues to enhance this project!


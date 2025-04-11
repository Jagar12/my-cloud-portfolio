## Text Narrator with Amazon Polly & AWS Lambda

This project gave me valuable experience working with **Amazon Polly**, sparking a renewed interest in **machine learning services**. I explored various features of Polly, including the ability to adjust **voice**, **pitch**, and **speed** parameters.

The main goal of the project was to develop a **text narrator**. A piece of text is input, converted to speech using Amazon Polly, and the resulting audio is saved into an **S3 bucket**.

---

## Project Workflow

1. **IAM Role Creation**  
   Created an IAM role to allow Lambda access to Amazon Polly and S3.

2. **S3 Bucket Setup**  
   Created a secure S3 bucket to store the output audio files.

3. **Lambda Function Development**  
   Configured a Node.js Lambda function that converts text to speech and stores the audio in the S3 bucket.

4. **Testing**  
   Successfully tested the Lambda function by passing JSON input and verifying output in S3.

---

## Future Plans

A future enhancement of this project would be to build a **web-based UI** that allows users to:
- Enter custom text
- Submit it to the backend Lambda function
- Receive and play back the generated audio file on the frontend

Stay tuned!

---

## Project Notes

1. The Lambda function:
   - Enables AWS SDK communication with Amazon Polly and S3
   - Waits for input and triggers processing
   - Converts input text to speech
   - Sets voice characteristics (voice, format, pitch, etc.)
   - Sends the text to Polly and stores the result in S3
   - Returns a success message or error if something goes wrong

2. ⚠️ **Be sure to replace** `YOUR-BUCKET-NAME` **with your actual S3 bucket name** in the Lambda code.

---

## Services Used

- **Amazon Polly**
- **AWS Management Console**
- **AWS IAM**
- **AWS Lambda**
- **Amazon S3**


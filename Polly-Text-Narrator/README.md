
# Text Narrator Using Amazon Polly and AWS Lambda

This project uses Amazon Polly, AWS Lambda, and Amazon S3 to convert text into speech and store the generated audio files.

I was interested in exploring Amazon Polly because of its text-to-speech capabilities and the different ways it could be used in applications. Working with Polly also increased my interest in AWS machine learning services.

For this project, I wanted to build a simple text narrator that takes text as input, converts it into speech using Amazon Polly, and saves the resulting audio file in an S3 bucket. I also spent some time exploring different voice settings, including pitch and speaking speed.

---

#### AWS Services and Tools

- **Amazon Polly** - Converts text into speech.
- **AWS Lambda** - Runs the Node.js function that processes text and generates audio.
- **Amazon S3** - Stores the generated audio files.
- **IAM** - Manages permissions between Lambda, Polly, and S3.
- **AWS Management Console** - Used to configure and manage the AWS resources.

#### How I Set It Up

1. Created an IAM role to give Lambda the necessary permissions to access Amazon Polly and S3.
2. Created an S3 bucket to store the generated audio files.
3. Configured a Node.js Lambda function to process text input and communicate with Polly.
4. Set up the function to save the generated audio files in the S3 bucket.
5. Tested the Lambda function using JSON input and verified that the audio files were successfully saved to S3.

#### How the Lambda Function Works

The Lambda function handles the text-to-speech process by:

1. Using the AWS SDK to communicate with Amazon Polly and S3.
2. Receiving text input through a JSON event.
3. Processing the input and configuring the voice settings.
4. Sending the text to Amazon Polly for speech synthesis.
5. Saving the generated audio file to the S3 bucket.
6. Returning a success message or an error if the process fails.

The function can be configured to use different voices, audio formats, and speech settings depending on the desired output.

#### Configuration

Before running the Lambda function, replace `YOUR-BUCKET-NAME` in the code with the name of your own S3 bucket.

The Lambda execution role also needs the appropriate IAM permissions to access Amazon Polly and write files to S3.

#### Results

After testing the Lambda function, I was able to successfully convert text into speech and store the resulting audio files in S3.

This confirmed that Lambda could communicate with Polly, process the text input, and save the generated audio without needing to run the code locally.

---

#### What I Learned

This project gave me more hands-on experience working with Amazon Polly and helped me better understand how AWS services can be connected to automate a process.

I also gained more experience configuring IAM permissions, working with Lambda functions, and using S3 to store generated files.

One feature I'd like to add in the future is a simple web interface where users can enter their own text, submit it to the Lambda function, and listen to the generated audio directly in their browser.

I think this would be a useful next step in turning the project into a more complete application.


# 🌐 Language Translation Bot with Amazon Lex

In this project, I built a **language translation chatbot** using **Amazon Lex**. The chatbot allows users to request a translation by providing a target language and the text they want to translate. Once submitted, the chatbot responds with the translated text using **Amazon Translate**.

---

## Project Overview

- **User Interaction**: The chatbot receives a user’s request, extracts the desired language and the text to be translated, then replies with the translated version.
- **Chatbot Setup**: I started by creating an empty chatbot and defining:
  - **Intents**: Representing the goal behind a user request.
  - **Slots**: Variables extracted from the user's input (e.g., target language and text).
- **User Experience Enhancements**: I added custom messages to provide:
  - Successful translation confirmations
  - Error responses
  - Polite and conversational feedback

---

## IAM Role Configuration

To allow the Lambda function to access the services it required, I created an **IAM role** with:
- Basic Lambda execution permissions
- Access to **Amazon Translate**

---

## Lambda Function Details

I developed a Lambda function that:
- Extracts the input text and target language from the chatbot
- Supports multiple languages
- Translates the input using **Amazon Translate**
- Returns a formatted response to Lex
- Handles errors and sends appropriate messages back to the user

I also updated the code to allow **lowercase** inputs for the target language (e.g., "french" instead of "French"), improving usability and reducing confusion for end users.

---

## Testing and Iteration

During initial testing, I encountered an error. After carefully reviewing the code, I made the necessary adjustments and successfully deployed the chatbot.

One key improvement was:
> Allowing users to input the desired language in both **lowercase and capitalized form**, making the bot more intuitive and user-friendly.

After implementing this, I tested again and received all the expected responses and translations.

---

## Lessons Learned

This project gave me hands-on experience with:
- A new AWS service: **Amazon Lex**
- Creating and integrating Lambda functions
- Writing and debugging Python code for AWS
- IAM role configuration
- Reading and applying **AWS documentation** to configure and extend functionality

It was a fun and rewarding challenge that sharpened my **problem-solving**, **troubleshooting**, and **cloud development** skills.

---

## 🛠AWS Services Used

- [Amazon Lex](https://aws.amazon.com/lex/)
- [AWS Lambda](https://aws.amazon.com/lambda/)
- [AWS IAM](https://aws.amazon.com/iam/)
- [Amazon Translate](https://aws.amazon.com/translate/)

---

> *Thanks for checking out this project! Feel free to fork or explore the code to build your own version.*


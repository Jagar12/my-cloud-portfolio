# TaskTide - AI-Powered Daily Task Scheduler

## Project Overview
TaskTide is an AI-generated daily task scheduler application built using PartyRock, powered by Amazon Bedrock. This application helps users structure their day efficiently by generating a schedule based on their input. It incorporates various widgets such as work hours, task list, time allocation, a motivational quote and image, a schedule assistant chat, and a final generated schedule. Once the necessary inputs are provided, the application generates a motivational quote, a motivational picture, and a structured schedule that includes optimal arrangement of tasks and included breaks.

## Services Used
- **PartyRock**, powered by **Amazon Bedrock**

- ![Alt text](PartyRock-Project/PartyRock.png)

## Features
✅ AI-generated daily task schedule  
✅ Customizable task list with time allocation  
✅ Motivational quote and image generation  
✅ Interactive schedule assistant chat  
✅ Automated widget synchronization for a seamless experience  
✅ User-friendly interface optimized for efficiency  

## Overview
This project was developed with the understanding that not everyone has a technical background, yet many could benefit from AI-driven tools for productivity. Exploring PartyRock and Bedrock enabled me to experiment with emerging AI-powered applications that enhance daily life.

### **Approach & Implementation**
I started by prompting PartyRock with:  
> "Generate a daily task scheduler."

This resulted in multiple AI-generated widgets that prompted additional user inputs, such as:
- Working hours
- Existing commitments
- Task list

To refine the functionality, I restructured and customized the widgets, ensuring they appeared in the optimal order for user interaction. I also edited each widget’s title, model, and prompts to ensure accurate references between widgets. For example, I created a **Time to Complete a Task** widget and referenced it in the **Generated Schedule** widget so that time blocks could be properly allocated.

Once the core scheduling components were finalized, I enhanced the user experience by adding motivational elements. A **motivational quote** widget was integrated, and the **motivational image** widget referenced the quote to generate a relevant image. These additions helped create a more engaging and positive user experience.

### **Testing & Prompt Engineering Insights**
After completing the first version, I decided to experiment with prompt engineering. Initially, I provided minimal instruction to the AI and manually adjusted the widgets. In my second attempt, I refined the prompt:

> "Create a daily task scheduler application which takes tasks and time required for tasks as input, and provides a schedule, a motivational quote, a motivational image, and a chatbot for optimizing the schedule."

This revised prompt generated a nearly identical application **without** requiring manual modifications, demonstrating the power of well-structured AI prompts.

## Key Takeaways
- **Prompt engineering** significantly influences AI-generated outputs.  
- **Customization** allows for greater control and user optimization.  
- **AI-driven platforms like PartyRock & Bedrock** make app development accessible to non-technical users.  

## Live Application
Check out **TaskTide**: [TaskTide on PartyRock](https://partyrock.aws/u/juliagarcia/FgansJz-v/TaskTide)

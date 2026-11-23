
# TaskTide - AI-Powered Daily Task Scheduler

TaskTide is a daily task scheduling application I built using PartyRock, an AI application-building tool powered by Amazon Bedrock.

The application allows users to enter their tasks, working hours, and time needed to complete each task. Based on that information, it generates a daily schedule with allocated time blocks and breaks.

TaskTide also includes a motivational quote, an AI-generated image, and a chatbot that users can interact with to make adjustments to their schedule.

I wanted to explore PartyRock because of how accessible it makes AI application development, even for people without a technical background. I thought a daily task scheduler would be a useful way to experiment with the platform while building something practical.

---

#### AWS Services and Tools

- **PartyRock** - Used to build and customize the application through AI-generated widgets.
- **Amazon Bedrock** - Provides the generative AI capabilities behind PartyRock.

#### Application Features

- AI-generated daily schedules based on user input.
- Customizable task lists and time allocations.
- Motivational quotes and AI-generated images.
- Interactive chatbot for adjusting and improving schedules.
- Connected widgets that reference information from other parts of the application.
- Simple interface designed to make daily planning easier.

#### How I Built It

I started by giving PartyRock a simple prompt:

> Generate a daily task scheduler.

PartyRock generated several widgets that allowed users to enter information such as:

- Working hours
- Existing commitments
- Daily tasks

After reviewing the initial application, I made several adjustments to improve how the widgets worked together.

I reorganized the layout, updated widget titles, and modified the prompts and model settings to better fit the application's purpose.

One of the changes I made was creating a **Time to Complete a Task** widget. I then referenced this widget in the **Generated Schedule** widget so that the application could account for how much time each task would require.

Once the scheduling features were working, I added a motivational quote widget and an image generation widget. The image widget references the generated quote to create a related image.

I wanted these additions to make the application a little more engaging while keeping the scheduling functionality as the main focus.

#### Testing Different Prompts

After completing the first version, I wanted to see how much of the application PartyRock could generate without requiring manual adjustments.

My original prompt was fairly basic, so I decided to try a more detailed version:

> Create a daily task scheduler application which takes tasks and time required for tasks as input, and provides a schedule, a motivational quote, a motivational image, and a chatbot for optimizing the schedule.

The results were interesting. PartyRock generated an application that was nearly identical to the version I had spent time manually customizing.

This helped me understand how much of a difference a well-written prompt can make when working with generative AI tools.

Rather than having to adjust each widget individually, I was able to describe the functionality I wanted upfront and get a much more complete result.

#### What I Learned

This project gave me an opportunity to experiment with Amazon Bedrock through PartyRock and learn more about how generative AI can be used to build practical applications.

One of my biggest takeaways was the importance of prompt engineering. Small changes in how instructions are written can make a noticeable difference in the results.

I also learned more about connecting widgets, managing references between them, and customizing AI-generated applications to better fit a specific purpose.

What stood out to me most was how accessible PartyRock makes application development. Even without extensive programming experience, users can experiment with AI and create tools that solve everyday problems.

---

#### Try TaskTide

The application is available on PartyRock:

[TaskTide - Daily Task Scheduler](https://partyrock.aws/u/juliagarcia/FgansJz-v/TaskTide)


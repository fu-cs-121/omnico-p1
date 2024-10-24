{{user.first_name }}, it's your first day at OmniCo and you open your email to see the following message:

<div style="display: flex; flex-direction: column; border: 1px solid #ddd; font-size: 16px; font-family: sans-serif; line-height: 1.2em; box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;">
<div style="border-bottom: 1px solid #ddd; width: 100%; padding: 10px 20px; color: #666;">From: Sophia Lewis (sophia.lewis@omni.co)</div>
<div style="border-bottom: 1px solid #ddd; width: 100%; padding: 10px 20px; color: #666;">Subject: Unlocking Insights in Euphoria's User Engagement Data</div>
<div style="padding:20px 40px;">
Dear {{user.first_name}},

I trust you're thriving within the limitless realms we're crafting here at OmniCo.

We've been making some exciting strides with our social VR platform, **Euphoria**, aiming to elevate user experiences to unprecedented levels. Recently, we've implemented three distinct content feed algorithms to see how they influence user engagement and overall mood:

- **JoyStream**: Curates content to amplify positivity and happiness.
- **SerenityFlow**: Focuses on providing calming and peaceful experiences.
- **DeepPulse**: Delves into a broader spectrum of emotions to deepen user interaction.

We've gathered a wealth of data since their deployment, and some of the patterns emerging—especially with **DeepPulse**—are quite intriguing. It appears to influence users' moods in unexpected ways, offering us a unique opportunity to understand and perhaps even guide user experiences more effectively.

I've set up a secure repository for you on OmniGit, our internal collaboration platform. You can access it using the secure link below. The dataset includes user session logs, engagement metrics, mood ratings, and other relevant information.

As you explore this data, feel free to consult the **OmniCodex**, our internal guide filled with programming patterns and best practices. It should serve as a helpful companion on your analytical journey.

We're eager to hear your insights. Sometimes, the most subtle data points can illuminate paths we hadn't considered before. Your fresh perspective might just be the key to unlocking new dimensions of user engagement.

Looking forward to your findings.

Warm regards,

Sophia Lewis
Lead Research Analyst
OmniVerse Division, OmniCo

<div style="font-size: 11px; color: #666">
CONFIDENTIALITY NOTICE: This message contains proprietary information of OmniCo and is protected by the OmniCo Cybernetic Legal AI (CLAIR) system. Unauthorized use or disclosure is strictly prohibited and may result in immediate action, including significant penalties. By proceeding, you acknowledge and agree to these terms across all timelines. Remember, at OmniCo, we’re not just shaping the future—we own it.
</div>

</div>
</div>

---

# Instructions for You

1. **Review the Email Carefully**

   - Understand what's being asked. Identify the main objectives, and pay attention to any nuances, especially regarding the **DeepPulse** algorithm.

2. **Design a Specification Document**

   - Outline your plan for analyzing the data.
   - Define the questions you aim to answer.
   - Note any assumptions or considerations.

3. **Set Up Your Development Environment**

   - Clone the repository from OmniGit using the link below
     - Copy the repository url from the [classroom link](https://classroom.github.com/a/2DJMmKAd). This is the blue highlighted link after you accept the assignment.
     - Open a new window in VSCode (File > New Window)
     - Click the Source Panel (branch icon) and then "Clone Repository"
     - Paste in the URL and select a location to save the repository
     - Open the repository folder in VSCode
     - Add your name to the top part of your `report.md` and commit/push it back to Github
   - Be sure to reference the [project codex](https://github.com/fu-cs-121/omnico-p1/blob/main/codex.md) as you code through the challenges.

4. **Analyze the Data**

   - Use Python to read and process the dataset (this is done for you in this project)
   - Follow the `TODO: ` comments carefully to complete the code
   - Perform calculations to determine:
     - Average mood ratings for each algorithm.
     - Total number of user sessions per algorithm.
     - Average session duration for each algorithm.
   - Look for patterns or anomalies, particularly those related to **DeepPulse**.

5. **Prepare Your Findings**

   - Write a Python script that prints a summary of your findings to the terminal using the output example below
   - Ensure the output is clear and well-formatted.

6. **Write a Delivery Report**

   - Write you report in the `report.md` file and follow the template provided.
   - Document your methodology, observations, and any insights.
   - Discuss any ethical considerations or unexpected findings.
   - Use professional language suitable for internal communication.

7. **Submit Your Work**

   - Commit your Python script and delivery report back to the OmniGit repository.
   - Follow the coding standards outlined in the **OmniCodex**.
   - Ensure your code is well-documented and easy to follow.

---

### Example Output

Afer analyzing the data, you might generate output that looks something like this:

```plaintext
Euphoria User Engagement Analysis Report
----------------------------------------

Average Happiness Rating per Algorithm:
- JoyStream: 8.50
- SerenityFlow: 7.00
- DeepPulse: 5.00

Total Number of Sessions per Algorithm:
- JoyStream: 4
- SerenityFlow: 3
- DeepPulse: 3

Average Session Duration per Algorithm:
- JoyStream: 37.50 minutes
- SerenityFlow: 30.00 minutes
- DeepPulse: 45.00 minutes

Highest Average Happiness Rating:
- JoyStream with an average happiness rating of 8.50

Longest Average Session Duration:
- DeepPulse with an average session duration of 45.00 minutes
```

By following these steps, you'll not only fulfill the task at hand but also contribute to our collective mission of enhancing user experiences in profound ways. Your analysis could play a pivotal role in shaping the future of Euphoria.

Good luck, and don't hesitate to reach out if you have any questions.

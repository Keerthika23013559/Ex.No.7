# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:01-11-2005
# Register no:212223240071
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 

ChatGPT / OpenAI API (Core engine for prompt interaction)

Prompt Engineering Techniques (Role prompting, structured prompts, parameterized prompts)
# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

## Project Concept: “Your Personal Productivity Assistant”

The assistant will:

1.Organize daily tasks

2.Schedule reminders

3.Suggest wellness tips

4.Answer general questions

5.Adapt to user preferences through prompts

## PHASE 1 — Basic Prompt (Manual)

## Prompt:

“Help me plan my tasks for today.”
## Example Output:
```
Your Tasks for Today:
- 8:00 AM – Check emails
- 10:00 AM – Attend team meeting
- 1:00 PM – Work on project
- 7:00 PM – Exercise
```

## This is the most basic interaction — no customization, just a simple to-do list.

## Prompt:

“Plan my daily schedule. I have meetings at 10 AM and 3 PM. I also want to include 2 hours for project work, 30 mins for wellness, and some personal time in the evening.”

## Example Output:

```
📅 Daily Schedule:
8:00 – 9:00 AM: Morning routine & exercise  
10:00 – 11:00 AM: Team Meeting  
11:30 – 1:30 PM: Project Work  
3:00 – 4:00 PM: Client Call  
6:00 – 7:00 PM: Personal Time (Hobby/Family)  
9:00 – 9:30 PM: Wellness Activity (Meditation/Reading)
```

Here, we’re giving structured input so ChatGPT can create a more personalized plan.

## PHASE 3 — Role Prompt + Format Instruction

## Prompt:

“You are my personal productivity assistant. Create a detailed daily plan with the following:

Meetings: 10 AM, 3 PM

Project work: 2 hours

Wellness: 30 minutes

Output format: table with time, activity, and notes.”

## Example Output:

<img width="675" height="355" alt="image" src="https://github.com/user-attachments/assets/485149d4-c166-4b16-a822-0b5a07fa1c3d" />


## PHASE 4 — Turning Prompts into an Application

Feature Flow:

User inputs → Meetings, work duration, preferences, goals

App generates structured prompt → Sends to ChatGPT

ChatGPT → Returns personalized plan

App displays as table, timeline, or chatbot-style conversation

Optional: Store preferences for next sessions


## Example User Input UI:
```
- Meeting times: [10 AM, 3 PM]
- Work duration: 2 hours
- Wellness time: 30 min
- Preferences: morning exercise
```

## Output UI:
```
📅 Daily schedule
🔔 Reminders list
🌿 Wellness tip of the day
🧠 Smart suggestions
```
## Prompt Engineering Techniques Used:

<img width="805" height="475" alt="image" src="https://github.com/user-attachments/assets/a3b14794-390b-41f6-80b1-0182071d3944" />

# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.

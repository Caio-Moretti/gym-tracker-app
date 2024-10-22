# Objective
**Context**: I use an Excel file to track my workouts, which includes:

- **Workout overview**: A schedule with exercises and sets for each day.
- **Detailed tracking per workout**: Each workout has its own sheet, where I record sets, reps, weight, and RIR.
    - This sheet also has useful information like how many sets I should do per set and the repetition range.
> Each workout sheet is divided by week, allowing me to compare progress week by week.

The goal of this application is to automate my current workout tracking from Excel into a web app. Initially, it will be free to use, and once the MVP is ready, I'll add payment options and launch it publicly.

# Stack

- NextJS
- Shadcn UI
- Supabase
- Vercel
- Tailwind
- AI:
    - ChatGPT
    - V0

# Functional Requirements
- I need to be able to write the weight, reps and RIR of each set I'm doing in real time;
- I need to be able to check the past sets so I can track my progress and have a reference for the next workout;
- I need to be able to define previously my workouts, setting the number of sets per exercise and range of repetitions I should do;
- Later, should be good to add statistics like number of sets I'm doing in total per week and total of sets per exercise. Of course, progress statistics will be a natural thing to add later.
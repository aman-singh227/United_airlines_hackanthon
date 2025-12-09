## Problem Statement~
Frontline teams at United Airlines are responsible for ensuring every flight departs on time and is operationally ready. However, not all flights are equally easy to manage. Certain flights pose greater complexity due to factors such as limited ground time, higher volumes of checked or carry-on baggage, and specific customer service needs that often increase with passenger load.
Currently, identifying these high-difficulty flights relies heavily on personal experience and local team knowledge. This manual approach is inconsistent, non-scalable, and risks missing opportunities for proactive resource planning across the airport.
To address this, you are tasked with developing a Flight Difficulty Score that systematically quantifies the relative complexity of each flight using the datasets provided, which span two weeks of departures from Chicago O’Hare International Airport (ORD).

## Objective~
The goal is to design a data-driven framework that:
1. Calculates a Flight Difficulty Score for each flight using flight-level, customer, and station-level data.
2. Identifies the primary operational drivers contributing to flight difficulty to enable proactive planning and optimized resource allocation.

## Deliverables~
1. Exploratory Data Analysis (EDA)
What is the average delay and what percentage of flights depart later than scheduled?
How many flights have scheduled ground time close to or below the minimum turn mins?
What is the average ratio of transfer bags vs. checked bags across flights?
How do passenger loads compare across flights, and do higher loads correlate with operational difficulty?
Are high special service requests flights also high-delay after controlling for load?

2. Flight Difficulty Score Development
Build a systematic daily-level scoring approach that resets every day. Below are the outputs required:
Ranking: Within each day, order flights by their difficulty score so that the highest-ranked flights represent the most difficult to manage.
Classification: Group flights into three categories — Difficult, Medium, or Easy — based on rank distribution.

3. Post-Analysis & Operational Insights
Summarize which destinations consistently show more difficulty.
What are the common drivers for those flights?
What specific actions would you recommend based on the findings for better operational efficiency?


<img width="867" height="497" alt="United airlines dashboard" src="https://github.com/user-attachments/assets/07941e35-a3f8-44ed-af1a-b4254804bf31" />


<img width="839" height="472" alt="05 10 2025_21 38 56_REC" src="https://github.com/user-attachments/assets/9ff98b7e-6dab-4e4f-938a-a75468d203e4" />



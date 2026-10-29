# AI Study Planner

AI-powered student study planner built for the Generative AI Lab (Practical Assignment No. 7).

## Features
- Input form: name, subject, topics, study hours/day, exam date, knowledge level
- AI-generated timetable, topic priorities (High/Medium/Low), revision dates, practice recommendations, tips and exam strategy
- Progress tracker, level-based personalized tips
- Prompt selector (Basic / Structured / Advanced) for prompt experiments
- Extension: AI quiz generator (5 MCQs + 5 short-answer questions with answers and explanations)

## Run
```
python3 -m http.server 8000
```
Open the forwarded port in Codespaces, expand "AI connection", then enter your API key and model name.

## Note
The API key is typed into the page and never stored. For production, move the AI call to a backend server.

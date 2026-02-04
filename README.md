Travel Itinerary Generator

This project is a web application that generates personalized travel itineraries using AI.
Users enter their travel details on the website, and an AI-generated travel plan is sent to their email.

The frontend handles data collection, while n8n manages automation, AI processing, and email delivery.

Frontend

The frontend files are available in this folder:
1) index.html
2) style.css
3) script.js
To host the frontend using GitHub Pages:
Push the code to a GitHub repository.
Go to Settings → Pages.
Select the main branch as the source.
Save the changes and wait for the site to deploy.

Frontend Development
AI was used as a development assistant.
It helped with:
Creating the glassmorphism-based CSS design.
Structuring the HTML form.
Writing the initial JavaScript logic for sending POST requests to the webhook.   
Automation Logic (n8n)
Model Used: llama-3.3-70b-versatile(Groq)

The AI acts as a travel expert.
It receives structured input from the frontend such as destination, budget, number of days, and preferences.
Based on this input, it generates a detailed travel itinerary.
The generated itinerary is sent directly to the user via email.

Design Decisions

No backend server: The project does not use a traditional backend. All logic is handled using client-side JavaScript and n8n.
Lightweight setup: No frameworks or databases are used.

User data is only processed by the n8n workflow and is not stored permanently.
Privacy focused: User data is only processed by the n8n workflow and is not stored permanently.

If you want, I can also:

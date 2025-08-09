# N8N_Personal-Holiday-Planner-Agent

This project is an AI-powered personal holiday planner built using n8n, designed to automate short trip planning based on upcoming holidays. The system integrates tools like Google Calendar, Google Sheets, OpenWeatherMap, Gmail, and OpenAI to deliver personalized travel suggestions directly to the user’s inbox.
The agent checks for upcoming holidays in the calendar, cross-references a curated list of destinations near Gurgaon, and uses weather data to filter suitable options. Once a destination is selected, it generates a customized holiday plan and emails it to the user. Optionally, it can also create a calendar event for the trip.
Key Features:\n
✅ Detects holiday dates from the calendar
✅ Checks weather conditions for the travel day
✅ Recommends nearby travel spots based on distance and duration
✅ Sends a personalized email using AI-generated content
✅ Integrates seamlessly into user’s schedule and tools
✅ Can be scheduled to run daily or on-demand
Tech Stack:
n8n (workflow automation)
OpenAI (chat model for message generation)
Google Sheets (destination data)
Google Calendar (holiday detection and event creation)
OpenWeatherMap API (weather forecasting)
Gmail API (email delivery)

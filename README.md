# TravelPartner-Chatbot

# 🧳 Travel Genie - AI-Powered Trip Planner

**Travel Genie** is an AI-driven travel assistant that helps users plan trips, save itineraries, integrate with Google Calendar, and receive personalized recommendations via email. The project leverages **Flask**, **OpenAI GPT**, **Airtable**, and **Google Calendar API** to provide a seamless travel planning experience.

---

## 🚀 Features

✅ **AI-Powered Trip Planner** – Generates personalized travel plans based on user preferences.  
✅ **Save Itineraries** – Stores travel plans in **Airtable** for easy access.  
✅ **Google Calendar Integration** – Automatically adds travel plans to Google Calendar.  
✅ **Email Notifications** – Sends travel plans via email.  
✅ **Personalized Recommendations** – Fetches recommendations for attractions, restaurants, and activities.  
✅ **API-Based Backend** – Built using **Flask**, supporting multiple endpoints.  

---

## 📂 Project Structure
📦 TravelGenie ┣ 📜 airtable_integration.py # Handles saving data to Airtable ┣ 📜 calendar_integration.py # Integrates with Google Calendar API ┣ 📜 config.py # Loads environment variables ┣ 📜 email_integration.py # Handles email notifications ┣ 📜 main_main.py # Flask API with various endpoints ┣ 📜 openai_integration.py # Uses OpenAI to generate travel plans ┣ 📜 recommendation_integration.py # Fetches travel recommendations using OpenAI ┣ 📜 credentials.json # Google API credentials (Do not expose publicly!) ┣ 📜 requirements.txt # Required dependencies ┗ 📜 README.md # Project documentation

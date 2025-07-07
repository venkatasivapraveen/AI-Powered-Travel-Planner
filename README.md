# 🌍 AI-Powered Travel Planner

An intelligent travel assistant that takes a natural language request like  
**"Plan my trip to Tokyo in July"** and returns a personalized, complete travel plan.  
This project uses **LangGraph** as the backbone for modular orchestration and integrates multiple APIs to provide real-time, reliable travel insights.

---

## 🧠 Features

- ✨ **LLM-Powered Info Extraction**: Extracts city, travel dates, and currency from user prompts using OpenAI.
- 🌤️ **Live Weather Forecast**: Fetches 7-day forecasts using the OpenWeather API.
- 📍 **Top Attractions**: Retrieves must-see spots via Google Places API.
- 🏨 **Hotel Cost Estimation**: Estimates average accommodation prices for the destination.
- 💱 **Live Currency Conversion**: Converts budgets using real-time data from ExchangeRate API.
- 📝 **Itinerary & Summary Generation**: Uses Groq's LLM to build day-wise plans and friendly overviews.
- 🔁 **Modular LangGraph Workflow**: Uses a state machine approach to manage data flow and execution.

---

## 📦 Requirements

- **Python**: `3.8+`
- **APIs & Keys**:
  - [OpenAI API](https://platform.openai.com/account/api-keys)
  - [OpenWeather API](https://openweathermap.org/api)
  - [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview)
  - [ExchangeRate API](https://www.exchangerate-api.com/)



🌦️ Weather Assistant Agent (Pydantic-AI + OpenWeatherMap)
An AI-powered Weather Assistant built using Pydantic-AI, Groq LLaMA model, and the OpenWeatherMap API.
The agent understands natural language questions and fetches real-time weather data using a tool.

🚀 Project Overview

This project demonstrates how to build an Agentic AI application that:
Accepts user questions in natural language
Uses an AI agent to decide when to call tools
Calls OpenWeatherMap API to fetch live weather
Returns a friendly weather response


User: What is the weather in Mumbai?
Agent: It seems like the current weather in Mumbai is smoke with temperature 30°C.

🧠 Technologies Used

Python
Pydantic-AI Framework
Groq LLaMA-3.1 Model
OpenWeatherMap API
Requests Library
Pydantic (Structured Output)

📂 Project Workflow

User asks a weather question.
AI agent analyzes the query.
Agent calls the tool get_weather_forecast.
Tool fetches real-time weather data.
Agent formats and returns a friendly answer.
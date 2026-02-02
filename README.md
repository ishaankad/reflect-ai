Reflect AI

Reflect AI is a personal reflection journal that helps users track their thoughts, moods, and writing patterns over time, and generates weekly insights to encourage self-awareness and reflection.

Why I built this

I wanted to explore how software can help people better understand themselves. Instead of starting with a large AI model, I designed a system that first extracts meaningful patterns from user data, and then optionally enhances those insights using AI.

Features

Write and save reflections

Track mood (1–5 scale)

Weekly summaries with:

reflection count

average mood

common themes (word analysis)

personalized insights

Mood trend over time

Modular AI system (rule-based + optional LLM)

Tech Stack

Backend: FastAPI, Python

Database: SQLite, SQLAlchemy

Frontend: HTML, CSS, JavaScript

AI: Rule-based insight engine (LLM-ready architecture)

How it works

User reflections are stored in a database. Each week, the app analyzes mood data, word usage, and writing behavior to generate human-readable insights. The system is designed so AI-generated insights can be added without replacing the core logic.

Future Improvements

LLM-powered insight generation

Sentiment analysis

User accounts

Data visualization dashboard

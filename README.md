AINEWSAgentic

An AI-powered news aggregation and summarization app built with Streamlit, LangChain, and Tavily API.

Overview

AINEWSAgentic is a Streamlit-based application that automatically fetches the latest Artificial Intelligence news from trusted global sources, summarizes it using LLMs, and presents it in clean, readable markdown format.
It supports fetching daily, weekly, monthly, and yearly AI news summaries, which can be saved as .md files for future reference.

Features
 AI News Fetching – Retrieves AI-related news from around the world using the Tavily API.
 LLM Summarization – Uses a language model to summarize news articles in a structured, readable format.
Multiple Frequencies – Choose from:
Daily (last 24 hours)
Weekly (last 7 days or fixed week range)
Monthly (last 30 days)
Yearly (last 366 days)
Markdown Export – Saves summaries in AINews/ folder.
Streamlit UI – Interactive and easy-to-use interface.

Tech Stack
Python 3.10+
Streamlit – UI rendering
LangChain – Prompt handling and LLM integration
Tavily API – News data fetching
Groq API / LLM – Summarization
Markdown – Output formatting
